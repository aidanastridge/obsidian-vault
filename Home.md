
```meta-bind-button
label: Today
icon: calendar
hidden: false
class: “”
tooltip: “”
id: today
style: primary
actions:
  - type: command
    command: periodic-notes:open-daily-note
```

<br />


```meta-bind-button
label: Audio
icon: mic
hidden: false
class: “”
tooltip: “”
id: audio
style: primary
actions:
  - type: open
    link: "[[Vocode Log]]"
    newTab: true
```

<br />


```meta-bind-button
label: Walking
icon: footprints
hidden: false
class: “”
tooltip: “”
id: today
style: primary
actions:
  - type: open
    link: "[[Walking Log]]"
    newTab: true
```

<br />

```meta-bind-button
label: Map of Content
icon: globe
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: open
    link: "[[Map of Content]]"
    newTab: true

```

---
##### *999: Nine Hours, Nine Persons, Nine Doors*

`$= const value = Math.round(((dv.page('Global/Puzzles/999 - Nine Hours, Nine Persons, Nine Doors/999 Endings.md').file.tasks.where(t => t.completed).length) / (dv.page('Global/Puzzles/999 - Nine Hours, Nine Persons, Nine Doors/999 Endings.md').file.tasks).length || 0) * 100);
"<progress value='" + value + "' max='100'></progress>"`
##### *The Count of Monte Cristo*

`$= const value = Math.round(((dv.page('Global/Content/Sources/Books/The Count of Monte Cristo/TCOMC Chapters.md').file.tasks.where(t => t.completed).length) / (dv.page('Global/Content/Sources/Books/The Count of Monte Cristo/TCOMC Chapters.md').file.tasks).length || 0) * 100);
"<progress value='" + value + "' max='100'></progress>"`

---

```meta-bind-button
label: Jigsaws
icon: puzzle
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: open
    link: "[[Jigsaws]]"
    newTab: true

```

`$= const value = Math.round(((dv.page('Global/Puzzles/Resources/Jigsaws.md').file.tasks.where(t => t.completed).length) / (dv.page('Global/Puzzles/Resources/Jigsaws.md').file.tasks).length || 0) * 100);
"<progress value='" + value + "' max='100'></progress>"`

---

```meta-bind-button
label: Video Games
icon: gamepad
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: open
    link: "[[To Play]]"
    newTab: true

```

`$= const value = Math.round(((dv.page('Global/Content/To Do/To Play.md').file.tasks.where(t => t.completed).length) / (dv.page('Global/Content/To Do/To Play.md').file.tasks).length || 0) * 100);
"<progress value='" + value + "' max='100'></progress>"`

---

```meta-bind-button
label: Movies
icon: film
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: open
    link: "[[To Watch (Movies)]]"
    newTab: true

```


`$= const value = Math.round(((dv.page('Global/Content/To Do/To Watch (Movies).md').file.tasks.where(t => t.completed).length) / (dv.page('Global/Content/To Do/To Watch (Movies).md').file.tasks).length || 0) * 100);
"<progress value='" + value + "' max='100'></progress>"`

---

```meta-bind-button
label: Books
icon: book
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: open
    link: "[[To Read]]"
    newTab: true

```

`$= const value = Math.round(((dv.page('Global/Content/To Do/To Read.md').file.tasks.where(t => t.completed).length) / (dv.page('Global/Content/To Do/To Read.md').file.tasks).length || 0) * 100);
"<progress value='" + value + "' max='100'></progress>"`

