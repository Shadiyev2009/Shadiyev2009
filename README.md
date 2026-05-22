class FullstackDeveloper:

    def __init__(self):
        self.name = "Doniyor"
        self.location = "Uzbekistan 🇺🇿"
        self.role = "Fullstack Developer"
        self.languages_spoken = ["uz", "ru", "en"]
        
        # Твой стек технологий
        self.frontend = ["React.js", "JavaScript", "TailwindCSS", "Vite"]
        self.backend = ["Node.js", "Express.js", "Python", "Django"]
        self.databases = ["PostgreSQL", "SQL"]

    def say_hi(self):
        print("Tashrifingiz uchun rahmat! Welcome to my dev world!")
        print("Let's build some scalable and beautiful apps together! 🚀")


me = FullstackDeveloper()
me.say_hi()
