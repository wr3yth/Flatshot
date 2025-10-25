# Flatshot
Feed entire projects into LLMs or any other kinds of AI, without any extra mess. Flatshot flattens any project into a single file. designed to ignore irrelevant files and make a machine/human-readable file.


## 🚀 Installation

Clone this repository and/or copy flatshot.py into your project root.

```git clone https://github.com/yourusername/flatshot.git```
when you put the flatshot.py in your project's main folder, run it from command line.
```python flatshot.py```
that's it!

```
🚀 flatshot running... [██████████████████████████████] 100.0%
✨ Output saved as: flat-yourproject.md
📂 C:\Users\yourname\yourproject
⏱️  Completed in 2.06 seconds
```
the output "flat-yourproject.md" will look like this:

```
# 📦 flatshot Project Snapshot

**Generated:** 2025-10-26 00:20:59

## raw structure


├── assets
│   ├── script.js
│   └── styles.css
├── index.html
├── random folder
│   ├── another random folder
│   │   ├── yet another
│   │   │   └── random file
│   │   └── yet another another
│   │       ├── random file
│   │       ├── random file copy
│   │       └── random file copy 2
│   ├── random file
│   └── random file 2
└── readme.txt



### `index.html`
---html
!<!DOCTYPE html>
<html>
    <head>
        <title>random title</title>
        <link rel="stylesheet" href="/assets/styles.css">
    </head>
    <body>
        <p>your content</p>
        <script src="/assets/script.js" async defer></script>
    </body>
</html>


---
### `readme.txt`
---txt
# Flatshot
Feed entire projects into LLMs or any other kinds of AI, without any extra mess. Flatshot flattens any project into a single file. designed to ignore irrelevant files and make a machine/human-readable file.


##🚀 Installation

Clone this repository and/or copy flatshot.py into your project root.

```git clone https://github.com/yourusername/flatshot.git```
when you put the flatshot.py in your project's main folder, run it from command line.
```python flatshot.py```
that's it!



🚀 flatshot running... [██████████████████████████████] 100.0%
✨ Output saved as: flat-yourproject.md
📂 C:\Users\yourname\yourproject
⏱️  Completed in 0.07 seconds


the output "flat-yourproject.md" will look like this:


---
### `assets\script.js`
---js
console.log("hello nerd!")


---
### `assets\styles.css`
---css
:root{
    background-color: aqua;
}
p{
    font-size: large;
}


---
### `random folder\random file`

random content


---
### `random folder\random file 2`

random more content


---
### `random folder\another random folder\yet another\random file`

random content



### `random folder\another random folder\yet another another\random file`

random content


---
### `random folder\another random folder\yet another another\random file copy`

copied random content


---
### `random folder\another random folder\yet another another\random file copy 2`

copied again random content



```

