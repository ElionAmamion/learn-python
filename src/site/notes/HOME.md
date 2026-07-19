---
{"dg-publish":true,"permalink":"/home/","tags":["gardenEntry"],"dg-note-properties":{}}
---

Welcome to this Python and Pygame tutorial.
In this vault, there will be most of my knowledge and experience I've gathered so far and I will probably update this again at some point.

In these few pages you can learn from your first few lines of code up to a fully fledged project of your own.
Below you will find a data base with all files in here, so you can quickly look things up as you go;.
If you are a complete beginner to python and don't even have it installed, I'd recommend you start [[Basics/Installing Python\|here]].

---
> [!fail] Coming soon
> If you already know the basics of programming with variable and different data types? Maybe you should start here.
> Maybe you've already mastered functions and classes, give PyGame a try.


```base
filters:
  and:
    - file.basename != this.file.basename
    - not:
        - file.folder == "Data Types"
        - file.folder == "Functions"
properties:
  file.folder:
    displayName: category
views:
  - type: cards
    name: HOME
    groupBy:
      property: file.folder
      direction: ASC
    order:
      - file.name
    sort:
      - property: order
        direction: ASC
    image: note.banner
    imageAspectRatio: 0.5
    cardSize: 200

```
