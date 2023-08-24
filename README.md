```
fun main() {
    val aboutMe = AboutMe()
    println(aboutMe)
}

class AboutMe {
    val name = "Satish Vajiram"
    val designation = "Android Developer"
    val experience = "2+ Years"
    val email = "iamsatishema@gmail.com"
    
    val linkedIn = "https://www.linkedin.com/in/satishema"
    val twitter = "https://twitter.com/satish_ema"
    val instagram= "https://instagram.com/satish_ema"
    val github = "https://github.com/satishema"
    
    override fun toString(): String {
        return "Name: $name\n" +
               "Designation: $designation\n" +
               "Experience: $experience\n" +
               "Email: $email\n" +
               "LinkedIn: $linkedIn\n" +
               "Instagram: $instagram\n" +
               "Twitter: $twitter\n" +
               "GitHub: $github"
    }
}
```

