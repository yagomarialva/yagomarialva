# Hello there 👋

![visitors](https://visitor-badge.laobi.icu/badge?page_id=yagomarialva-br.yagomarialva-br)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)


```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class Student:
    def __init__(self):
        self.name = "Yago Marialva Bentes"
        self.role = "Estudante o/"
        self.location = "https://goo.gl/maps/j62SAvvmu78kCKZP6"
        self.knowledge_base = [
            "Front-end"
        ]
        self.knowledge_base.insert(0, "Data Science")

    def say_hi(self):
        print(
            """Oi, obrigado pela visita!

Meu nome é {name}, sou de {location}. no momento sou {role} e atualmente estou focando {focus} para melhorar minhas habilidades.

gosto de estudar várias coisas mas o que mais me especializei foi {knowledge_base}.""".format(
                name=self.name,
                location=self.location,
                role=self.role,
                focus=self.knowledge_base[0],
                knowledge_base=", ".join(self.knowledge_base[1:]),
            )
        )


me = Student()
me.say_hi()

## read me inspired on https://github.com/Zhenye-Na
```
