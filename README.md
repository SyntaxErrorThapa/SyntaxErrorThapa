
👨‍💻 GitHub Profile

class Profile:
    def __init__(self):
        self.name = "Pratik Thapa"
        self.title = "Programmer & Student"
        self.languages = ["Python", "Java", "C/C++", "JavaScript", "Bash"]
        self.interests = ["Full Stack Development", "Machine Learning", "Open Source"]
        self.humor_level = "High"  # Because coding should be fun!
    
    def __str__(self):
        return f"Hi there, I'm {self.name}, a {self.title}!"
