``` python
class ZadkielAvendano:
    def __init__(self):
        self.name = 'Zadkiel Avendaño'
    
    def who_am_i(self):
        self.year = 2005
        self.studies = 'Systems Engineering from the Metropolitan University of Caracas'
        self.pets = 'Bucky'
    
    def skills(self):
        self.frameworks = ['react', 'react-router']
        self.main_languages = ['python', 'java', 'javascript', 'css', 'html']
        self.learnings = ['typescript', 'flutter', 'c#', 'kotlin']

    def __str__(self):
        return f"I'm {self.name}, a {self.studies}."
        
me = ZadkielAvendano()
```
