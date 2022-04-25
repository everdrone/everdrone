```swift
struct Profile {
    let url = "https://neurocore.xyz"
    var stack = [
        "c++",
        "python",
        "javascript",
        "ruby"
    ]
    let quote = "i l(ove|ike) regexp?"
    let technologies = FullStack(
        frontEnd: [
            .nextjs,
            .svelte,
            .sass
        ],
        backEnd: [
            .django,
            .postgresql
        ],
        other: [
            .graphql,
            .aws
        ]
    )
}
```
