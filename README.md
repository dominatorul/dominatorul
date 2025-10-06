<h2 align="center">About Me </h2>

```python
from typing import Tuple, List, Dict

class Dominatorul:
    pass

class Attributes(Dominatorul):
    @property
    def contact(self) -> Tuple[str, str, str]:
        discord = "Dominatorul"
        telegram = "t.me/dominatorul"
        kofi = "https://ko-fi.com/dominatorul
        return f"Find me on Discord: {discord}, or on Telegram: {telegram}! Buy me a coffee: {kofi}"

    @property
    def life(self) -> Tuple[List[str], int]:
        hobbies = ['Gaming', 'Coding', 'Exploring the digital realm and Music']
        age = 21
        return f"At the ripe age of {age}, my life revolves around: {', '.join(hobbies)}."

    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str]]:
        skills = {
            'expert': ['Python'],
            'intermediate': ['C++', 'JavaScript'],
            'learning': ['Java']
        }
        expertise = ['Python']
        tools = ['VSCode and Magic Wand']
        return f"Behold my coding kingdom! I know {', '.join(expertise)} very well, and my preferred environments are {', '.join(tools)}!"


dominatorul_attributes = Attributes()

print(dominatorul_attributes.contact)
print(dominatorul_attributes.life)
print(dominatorul_attributes.coding)
