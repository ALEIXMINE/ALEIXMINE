### Hi there 👋<h2> I'm ALEIXMINE17</h2>

```python

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)


class Bio(metaclass=Meta):
    name        : str = "ALEIXMINE17"
    designation : str = "Full-Stack Developer, Game Developer"
    base        : str = "Spanish"
    website     : str = "aleixmine.github.io"


class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Python", "Batch", "Node.js", "Spigot API")
    databases   : Tuple[str, ...] = ("Mongo")
    frontend    : Tuple[str, ...] = ("HTML", "JS", "CSS", "React")


class Social(metaclass=Meta):
    youtube     : str = "ALEIXMINE17"
    twitter     : str = "aleixmine17"
```