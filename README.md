```
fun main() {
    val aboutMe = AboutMe()
    println("🚀 Welcome to the world of Satish Ema! Let me unveil the magic:")
    println(aboutMe)
}

class AboutMe {
    val name = "🌟 Satish Vajiram"
    val designation = "🚀 Android Alchemist"
    val experience = "📅 2+ Years of Coding Adventures"
    val email = "💌 Reach out to me at: iamsatishema@gmail.com"

    val linkedIn = "🌐 Connect with me on the professional canvas: ${link("LinkedIn", "https://www.linkedin.com/in/satishema")}"
    val twitter = "🐦 Follow my thoughts and tales on Twitter: ${link("Twitter", "https://twitter.com/satish_ema")}"
    val instagram = "📸 Explore my visual diary on Instagram: ${link("Instagram", "https://instagram.com/satish_ema")}"
    val github = "🔧 Discover my secret coding chamber on GitHub: ${link("GitHub", "https://github.com/satishema")}"

    override fun toString(): String {
        return """
            |Name: $name
            |Designation: $designation
            |Experience: $experience
            |Email: $email
            |$linkedIn
            |$twitter
            |$instagram
            |$github
        """.trimMargin()
    }

    private fun link(name: String, url: String): String {
        return "\u001B]8;;$url\u001B\\$name\u001B]8;;\u001B\\"
    }
}
```

