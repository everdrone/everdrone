```swift
struct Profile {
    let url = "https://neurocore.xyz"
    var stack = [
      "C/C++",
      "Python",
      "Javascript",
      "Ruby"
    ]
    let quote: String = "i l(ove|ike) regexp?"
    let technologies = FullStack(
      frontEnd: [
        .react,
        .sass
      ],
      backEnd: [
        .django,
        .rails
      ],
      other: [
        .graphql,
        .aws
      ]
    )
}
```
