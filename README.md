[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=39D353&vCenter=true&width=600&lines=%24+whoami;%3E+gabriel+reimberg+de+paiva;%3E+data+engineering+%26+data+science+enthusiast)](https://github.com/ArticN)

### `$ cat about_me.py`

```python
from dataclasses import dataclass, field


@dataclass
class Developer:
    name: str = "Gabriel Reimberg de Paiva"
    role: str = "Data Engineering & Data Science Enthusiast"
    main_language: str = "Python"

    familiar_with: dict = field(default_factory=lambda: {
        "data":      ["Pandas", "NumPy", "SQL"],
        "pipelines": ["ETL / ELT", "Airflow"],
        "ml":        ["scikit-learn"],
        "tooling":   ["Git", "Docker", "Linux"],
        "also_code": ["C", "C#"],
    })

    currently_learning: list = field(default_factory=lambda: [
        "PySpark", "Data Modeling", "Cloud Data Platforms",
    ])

    def status(self) -> str:
        return "building pipelines, breaking things, learning every day"


if __name__ == "__main__":
    print(Developer().status())
```

### `$ git log --stats`

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ArticN&show_icons=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=39d353&icon_color=39d353&text_color=c9d1d9" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ArticN&layout=compact&langs_count=6&hide_border=true&bg_color=0d1117&title_color=39d353&text_color=c9d1d9" alt="Top languages" />
</p>

<img src="https://streak-stats.demolab.com?user=ArticN&hide_border=true&background=0D1117&ring=39D353&fire=39D353&currStreakLabel=39D353&currStreakNum=C9D1D9&sideNums=C9D1D9&sideLabels=8B949E&dates=8B949E&stroke=30363D" alt="Contribution streak" />

### `$ ping gabriel`

`>` [`linkedin`](https://www.linkedin.com/in/gabriel-reimberg) &nbsp;·&nbsp; [`email`](mailto:gabriel.preimberg@gmail.com) &nbsp;·&nbsp; [`github`](https://github.com/ArticN)
