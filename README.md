[![ALEIXMINE's GitHub stats](https://visitor-badge.laobi.icu/badge?page_id=ALEIXMINE.readme.visitor-badge)](https://github.com/ALEIXMINE/)

<h1 align="center"> Hi there 👋 I'm ALEIXMINE17</h1>

<hr>

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

<hr>


<h3 align="center">Stats</h3>
<div align="center">
    [![ALEIXMINE's GitHub stats](https://github-readme-stats.vercel.app/api?username=ALEIXMINE&show_icons=true&theme=merko)](https://github.com/ALEIXMINE/)
    [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ALEIXMINE&layout=compact&theme=tokyonight)](https://github.com/ALEIXMINE/)
</div>
<hr>

- Links to social networks and projects: https://aleixmine.github.io/
