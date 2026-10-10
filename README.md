# Interactive Resume Builder (Task 29)

A form-driven resume builder with a **live preview** that updates on every input event and a **print-friendly layout** (export to PDF).
Built during my Web Development internship at **Veda Technology**.

## Live Demo
https://<username>.github.io/resume-builder/

## Features
- Form for personal info, skills, education and experience
- Live preview panel (two-way data binding using the `input` event)
- Add / remove education and experience entries
- Skill bars chart (`HTML:90, CSS:85` becomes progress bars)
- Import / export resume data as **CSV**
- Print-specific stylesheet (`print.css`) to save as PDF
- Auto-saves in the browser (localStorage)

## Tech Stack
HTML5, CSS3, JavaScript (vanilla)

## Folder Structure
```
resume-builder/
├── index.html
├── css/
│   ├── style.css
│   └── print.css
├── js/
│   └── script.js
├── data/
│   └── sample-resume.csv
├── screenshots/
└── README.md
```

## How to Run
1. Clone: `git clone https://github.com/<username>/resume-builder.git`
2. Open in VS Code and run **Live Server** on `index.html`

## How to Export PDF
Click **Print / Save PDF**, choose **Save as PDF**, turn off *Headers and footers*, then Save.

## Screenshots


![Preview](screenshots/preview.png)



## Author
Joshan - Web Development Intern, Veda Technology
