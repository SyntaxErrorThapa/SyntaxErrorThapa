<center>
  <h1>👨‍💻 Pratik Thapa's GitHub Profile</h1>
</center>


```python
# They call me SyntaxError for a reason ...
class Profile:
    def __init__(self)
        self.name = "Pratik Thapa"
        self.title = "Programmer & Student"
        self.languages = ["Python", "Java", "C/C++", "JavaScript", "Bash"]
        self.interests = ["Full Stack Development", "Machine Learning", "Open Source"]
        self.humor_level = "High"  # Because coding should be fun!
    
    def __str__(self):
        return f"Hi there, I'm {self.name}, a {self.title}!"

    def skills(self):
        print("My Tech Stack: (a.k.a. the stuff that keeps me awake at night)")
        toolbelt = {
            "languages": ["Python", "Java", "C/C++", "JavaScript", "Bash"],
            "front_end_development": ["React", "Bootstrap", "Tailwind", "Sass", "CSS", "HTML"],
            "back_end_development": ["Node.js", "Express", "Flask"],
            "machine_learning": ["TensorFlow", "OpenCV", "PyTorch", "Pandas", "scikit-learn"],
            "database": ["MySQL", "PostgreSQL", "SQLite"],
            "devops": ["AWS", "Bash"],
            "others": ["Linux", "Git", "Arduino"]
        }
        
        for category, skills_list in toolbelt.items():
            skills_formatted = ", ".join(skills_list)
            print(f"{category.capitalize().replace('_', ' ')}: {skills_formatted}")
        
        print("# P.S. I also speak fluent 'Git'ish'. Commit, push, repeat.")
```

