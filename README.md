```
fun main() {
    val aboutMe = AboutMe()
    println("🚀 Hey there, curious soul! Let me introduce myself:")
    println(aboutMe)
}

class AboutMe {
    val name = "Satish Vajiram"
    val designation = "📱 Android Sorcerer"
    val experience = "✨ 2+ Years of Crafting Magic"
    val email = "📧 iamsatishema@gmail.com"

    val linkedIn = "🌐 Connect with me on LinkedIn: ${url("https://www.linkedin.com/in/satishema")}"
    val twitter = "🐦 Follow my adventures on Twitter: ${url("https://twitter.com/satish_ema")}"
    val instagram = "📸 Catch a glimpse of my life on Instagram: ${url("https://instagram.com/satish_ema")}"
    val github = "💻 Explore my spells on GitHub: ${url("https://github.com/satishema")}"

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

    private fun url(link: String): String {
        return "\u001B]8;;$link\u001B\\$link\u001B]8;;\u001B\\"
    }
}

```

