```swift
// MARK: - About Me

@Observable
final class EricCanalle: Identifiable {
    
    let id = UUID()
    
    struct Profile {
        let name = "Eric Canalle"
        var currentRole = "iOS Developer in Progress"
        let location = "Joinville, Brasil"
        var experience = "Building production-ready iOS apps with Swift & SwiftUI"
        var background = "Learning iOS development, focused on clean code and system design"
    }
    
    // MARK: - Current Status
    @State var currentFocus = "Building production-ready iOS apps with SwiftUI"
    var certifications = ["Swift 5", "Swift 6", "Xcode 15"]

    // MARK: - Contact
    let github = URL(string: "https://github.com/ecanalle")!
    let linkedin = URL(string: "https://www.linkedin.com/in/ecanalle/")!
    let email = "eric.canalle@icloud.com"
    
    // MARK: - Motto
    let philosophy = "Think Different"
}
```

## Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white&style=for-the-badge" alt="Swift"/>
  <img src="https://img.shields.io/badge/SwiftUI-0D96F6?logo=swift&logoColor=white&style=for-the-badge" alt="SwiftUI"/>
  <img src="https://img.shields.io/badge/Xcode-1575F9?logo=xcode&logoColor=white&style=for-the-badge" alt="Xcode"/>
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white&style=for-the-badge" alt="Git"/>
  <img src="https://img.shields.io/badge/SQL-555555?logo=code&logoColor=white&style=for-the-badge" alt="SQL"/>
</p>

## Focused On

- **[incident-log](https://github.com/ecanalle-dev/incident-log)** — iOS app for tracking and managing incidents · Built with SwiftUI & SwiftData
- **[swift-docs](https://github.com/ecanalle-dev/swift-docs)** — Swift documentation and learning resources
