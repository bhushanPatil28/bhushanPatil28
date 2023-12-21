# GitHub Profile Description

class CodeAdventurer:
    def __init__(self, name, role):
        self.name = name
        self.role = role

    def describe(self):
        return """
        Greetings, fellow coders! 👋 I'm {}—a {} currently crafting magic with lines of code.
        
        🌐 Aspiring to be a tech wizard, I'm on a relentless pursuit of knowledge and mastery in programming and artificial intelligence. 
        💻 GitHub is my canvas, where I weave intricate spells using Python, JavaScript, and whatever else comes my way.

        🚀 Currently embarking on a Bachelor's journey in Arts, with my eyes set on the coveted Master of Computer Application (MCA) degree.
        🔍 Exploring internships to bridge the gap between theory and real-world code sorcery.

        ⚡ Let's connect, collaborate, and maybe conjure some code together! 🧙‍♂️💡

        #CodeCrafting #AIEnthusiast #MCAJourney #GitHubAdventures #TechAlchemy
        """.format(self.name, self.role)

if __name__ == "__main__":
    code_adventurer = CodeAdventurer(name="Mayur", role="Passionate Programmer")
    print(code_adventurer.describe())
