- 👋 Hi, I’m @kuchidaxardito
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
kuchidaxardito/kuchidaxardito is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# flowchart

```mermaid
flowchart TB

    start([誕生]) --> do_work{働く?}
    do_work -->|yes| karoshi([過労死END])
    do_work -->|no| uejini([餓死END])
```


# sequence diagrams

```mermaid
sequenceDiagram

    actor me
    actor mother
    me ->> mother: 給料
    mother -->> me: おこづかい
```


# class diagrams

```mermaid
classDiagram
Noodle <|-- Ramen
Noodle <|-- Udon
Noodle <|-- Soba

Ramen <|-- Sapporo
Ramen <|-- Jiro

Udon <|-- Inaniwa
Udon <|-- Sanuki

Soba <|-- Sarashina
Soba <|-- Stand
```


# Pie chart

```mermaid
pie title favorite moves
    "Chairs": 200
    "Super Kick": 80
    "Suplex": 100
    "Table": 60
```
