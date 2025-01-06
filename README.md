## My Profile

Hello! Here's a snapshot of who I am:
```swift
struct Profile {
    let name: String
    let position: String
    let education: String
    let specialties: [String]
    let hobbies: [String]
}

let myProfile = Profile(
    name: "Reeen",
    position: "iOS Engineer at Yumemi Inc.",
    education: "Majored in International Politics",
    specialties: [
        "Swift",
        "UIKit",
        "SwiftUI",
        "MapKit",
        "Firebase",
        "Swift Package Manager",
        "MVVM Architecture",
        "Flux Architecture",
        "... and more!"
    ],
    hobbies: [
        "Traveling",
        "Playing darts",
        "Skiing",
        "Watching movies (especially the 007 series)",
        "Brewing coffee"
    ]
)

func introduce(profile: Profile) {
    print("Name: \(profile.name)")
    print("Position: \(profile.position)")
    print("Education: \(profile.education)")
    print("Specialties: \(profile.specialties.joined(separator: ", "))")
    print("Hobbies: \(profile.hobbies.joined(separator: ", "))")
}

introduce(profile: myProfile)
```

## My Github Status.  
![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=reeen21&theme=jolly)
[![GitHub Streak](https://streak-stats.demolab.com?user=reeen21&theme=jolly&hide_border=true&date_format=%5BY.%5Dn.j&mode=weekly)](https://git.io/streak-stats)
[![trophy](https://github-profile-trophy.vercel.app/?username=reeen21&theme=radical&no-frame=true)](https://github-profile-trophy.vercel.app/?username=reeen21&theme=radical&no-frame=true)
