### Hi there 👋

```python
class Bio(FullStackDeveloper):
    def __init__(self, name, title, company):
        self.name = name
        self.title = title
        self.company = company
    
    def aboutMe(self, info):
        self.info = info

kunalSharma = Bio('Kunal Sharma', 'Software Engineer', 'Elucidata')
kunalSharma.aboutMe({
    'Tools and Technology' : [],
    'Skills': [],
    'Hobbies': []
})
```
