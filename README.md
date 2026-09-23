# STEM HoloVerse

Interactive virtual STEM labs for Chemistry, Physics, and Biology. Learn by exploring hands-on experiments in the browser with no install required.

## Features

- Interactive science experiments with animations and feedback
- Responsive layout for mobile, tablet, and desktop
- Subject hubs for Chemistry, Physics, and Biology
- Pure HTML and CSS (open any page in a browser)

## Getting started

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Click **Enter the Lab** to choose a subject, or open any lab HTML file directly.

You can also serve the folder with a simple local server if you prefer:

```bash
# Python
python -m http.server 8000

# Node (npx)
npx serve .
```

Then visit `http://localhost:8000`.

## Project structure

```
Steam-Lab-master/
├── index.html              # Landing page
├── lab.html                # Subject picker (Science, Tech, Engineering, Math)
├── science.html            # Science hub
├── science-new.html
├── style.css               # Shared styles
├── Chemistry
│   ├── chem-main.html / chem-main-enhanced.html
│   ├── chem-h2o.html       # Water molecule lab
│   └── chem-nacl.html      # Salt / ionic bonding lab
├── Physics
│   ├── phys-main.html / phys-main-enhanced.html
│   ├── phys-forces.html
│   └── phys-gravity.html
├── Biology
│   ├── bio-main.html / bio-main-enhanced.html
│   ├── bio-cells.html
│   └── bio-genetics.html
└── Explorers
    ├── sci-atoms-explorer.html
    ├── sci-chemistry.html
    └── sci-molecule-world.html
```

## Subjects

| Subject   | Status   | Labs |
|-----------|----------|------|
| Science   | Available | Chemistry, Physics, Biology |
| Technology | Coming soon | - |
| Engineering | Coming soon | - |
| Math      | Coming soon | - |

## Tech

- HTML5
- CSS3 (shared `style.css` plus page-level styles)

## License

Use and modify freely for learning and education.
