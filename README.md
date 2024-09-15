### Hi there 👋

``` swift
import SwiftUI
import archon8

struct AyaanView: View {
    var hobbies = ["Coding", "Swimming", "Reading"]
    var location = ["37.8199° N, 122.4786° W"]
    var languages = ["Swift", "Next.js", "React.js"]
    var tools = ["FlipperZero", "XCode", "VSCode"]

    var body: some View {
        VStack(alignment: .leading, spacing: 10) {
            Text("Hobbies: \(hobbies.joined(separator: ", "))")
            Text("Location: \(location)")
            Text("Languages: \(languages.joined(separator: ", "))")
            Text("Tools: \(tools.joined(separator: ", "))")
        }
        .padding()
        .font(.system(size: 16, weight: .medium, design: .default))
    }
}

struct AyaanView_Previews: PreviewProvider {
    static var previews: some View {
        AyaanView()
            .previewLayout(.sizeThatFits)
            .padding()
            .previewDisplayName("Ayaan")
    }
}

```

<p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=ayaangrover&bg_color=30,0D1117,0D1117&title_color=fff&text_color=fff">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ayaangrover&layout=donut&bg_color=30,0D1117,0D1117&text_color=ffffff&title_color=ffffff">
</p>

<p align="center">
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=ayaangrover&theme=dark" />
    <img src="https://streak-stats.demolab.com?user=ayaangrover&theme=dark"/>
</p>
