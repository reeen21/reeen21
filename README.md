## My Profile

Hello! Here's a snapshot of who I am:
```swift
struct Profile: Introducible {
    let name: String
    let position: String
    let education: String
    let specialties: [String]
    let hobbies: [String]
}

let myProfile = Profile(
    name: "Reeen",
    position: "iOS Engineer at Accenture Song.",
    education: "Majored in International Politics",
    specialties: [
        "Swift",
        "SwiftUI",
        "Swift Concurrency",
        "MapKit",
        "Firebase",
        "Swift Package Manager",
        "Flux/Redux Architecture",
        "... and more!"
    ],
    hobbies: [
        "Traveling",
        "Skiing",
        "Watching movies (especially the 007 series)",
        "Brewing coffee",
        "Drink Whiskey"
    ]
)

func introduce(profile: Profile) {
    while true {
        print("Name: \(profile.name)")
        print("Position: \(profile.position)")
        print("Education: \(profile.education)")
        print("Specialties: \(profile.specialties.joined(separator: ", "))")
        print("Hobbies: \(profile.hobbies.joined(separator: ", "))")
    }
}

introduce(profile: myProfile)
```

![](https://raw.githubusercontent.com/reeen21/reeen21/output/github-contribution-grid-snake-dark.svg)

