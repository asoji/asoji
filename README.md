<p align="center">
  <img src="https://github.com/user-attachments/assets/98dec58f-f285-498b-9837-efdcaa659c74" width="768" />
</p>

```kt
fun main() {
    println(AboutMe(
        name = "asojidev",
        preference = mutableListOf(
            "they/them/xe/xim",
            "gay",
            "non-binary masc"
        ),
        occupation = mutableListOf(
            "Hobbyist software developer",
            "UI/UX Designer"
        ),
        groups = mutableListOf(
            "devOS: Sanity Edition [Lead Studio Head]",
            "Tricky Tanuki Studios [owned by devOS: Sanity Edition]",
            "Illumi Engineering"
        ),
        languages = mutableListOf(
            "Kotlin",
            "Java",
            "C#"
        ),
        socials = AboutMe.Socials(
            github = "@asoji",
            bluesky = "@asoji.gaywizard.xyz",
            mastadon = "@asojidev@nyanya.gay"
        ),
        profilePictureArtist = "@GreenyPika on Twitter"
    ))

    println(Projects(
        projects = mutableListOf(
            Pair("Softer Pastels",  "https://github.com/devOS-Sanity-Edition/SofterPastels"),
            Pair("Yiski",           "https://github.com/devOS-Sanity-Edition/yiski/"),
            Pair("EasyLogPlus",     "https://github.com/asoji/EasyLogPlus"),
            Pair("PopcornCounter",  "https://github.com/asoji/PopcornCounter"),
        )
    ))

    println(PCSpecs(
        link = "https://pcpartpicker.com/list/xTbjb2" // Go here for a more up-to-date PC Part Picker List
    ))


    TODO("Add more to this readme, this is all I could come up with for now :p")
}
```
