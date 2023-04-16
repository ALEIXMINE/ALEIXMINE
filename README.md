### Hi there 👋<h2> I'm Shivam</h2>

<img align='right' src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="230">

<h3> 👨🏻•💻 About Me </h3>

- 🤔 &nbsp; Exploring new technologies and developing software solutions and quick hacks.

- 🎓 &nbsp; Studying Computer Science and Engineering at IIIT Vadodara and coding stuffs.

- 🌱 &nbsp; Learning about Cloud Tech, Systems Design.

- ✍️ &nbsp; Pursuing Web Development as hobbies/side hustles.

<h3>🛠 To Learn</h3>

- 🔧 &nbsp; AWS | Docker🐳 | Firebase | flask

<hr>

<br/><br/>

[![Shivam's GitHub Stats](https://github-readme-stats.vercel.app/api?username=shivam0110&show_icons=true)](https://github.com/shivam0110)

<br/>

<br/>

<img src="https://github.com/nirala69/nirala69/blob/master/70804f7e25b11f29db904f2fa7b4cd9d.gif" width="350" align='right'>

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=shivam0110&show_icons=true)

<br><br>

<hr>

![Visitor count](https://visitor-badge.laobi.icu/badge?page_id=shivam0110.shivam0110)   <img src="https://media.giphy.com/media/dxn6fRlTIShoeBr69N/giphy.gif" width="30">

<hr>

```python

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)


class Bio(metaclass=Meta):
    name        : str = "Redowan Delowar"
    designation : str = "Data Scientist"
    company     : str = "ShopUp"
    base        : str = "Dhaka, Bangladesh"
    blog        : str = "rednafi.github.io/digressions"


class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Python", "Go", "Shell")
    databases   : Tuple[str, ...] = ("MySQL", "PostgreSQL", "Mongo", "Redis")
    misc        : Tuple[str, ...] = ("Docker", "Celery")
    ongoing     : Tuple[str, ...] = ("Django", "GraphQL")

<h1>A</h1>

class Social(metaclass=Meta):
    twitter     : str = "rednafi"
    linkedin    : str = "redowan"
```