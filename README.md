# Web Technology-I — Lab Tasks

A collection of lab exercises for **Web Technology-I**, covering HTML5, CSS3, Bootstrap, and core JavaScript.

**Student:** Dipesh Chaudhary (Roll No. 24101016)
**Program:** B.Tech in Information Technology
**University:** Lumbini Technological University, Institute of Engineering and IT, Nepalgunj, Banke

---

## Table of Contents

- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Lab Index](#lab-index)
- [Notes](#notes)

---

## Project Structure

```
Lab Task WebTech-I/
├── Audio/        # spy.mp4          (used in Lab 2, Task II)
├── Video/        # water.mp4        (used in Lab 2, Task II)
├── Files/        # Profile.pdf, CompTIA A+ 220-1201 Exam Objectives (4.0).pdf
├── Image/        # Aitwari.jpg, ltu.jpg
├── Lab1Task-I.html
├── Lab1Task-II.html
├── ...
└── Lab21Task-2.html
```

Every lab is a single, self-contained `.html` file (HTML, CSS, and JS in one place), named `Lab<N>Task-<M>.html`.

## Getting Started

No build tools or dependencies are needed.

```bash
# 1. Clone the repository
git clone https://github.com/dipesh-dev1/Lab-Report-WebTech.git
cd Lab-Report-WebTech

# 2. Open any lab in your browser
#    e.g. double-click Lab6Task-3.html, or:
open "Lab6Task-3.html"        # macOS
xdg-open "Lab6Task-3.html"    # Linux
start "" "Lab6Task-3.html"    # Windows
```

Tip: use the **Live Server** extension in VS Code for auto-reload while editing.

---

## Lab Index

### HTML Fundamentals

| Lab | File | Topic |
|-----|------|-------|
| 1 | `Lab1Task-I.html` | Basic HTML page structure (`html`, `head`, `body`, `h1`, `p`) |
| 1 | `Lab1Task-II.html` | Text formatting tags (`b`, `i`, `u`, `strong`, `em`, `mark`, `sub`, `sup`, `del`, `ins`) |
| 2 | `Lab2Task-I.html` | HTML5 semantic elements (`header`, `nav`, `section`, `article`, `footer`) |
| 2 | `Lab2Task-II.html` | HTML5 multimedia: `audio`, `video`, `embed`, `object` |
| 3 | `Lab3Task-I.html` | Embedding an image with custom width and height |
| 4 | `Lab4Task-I.html` | Hyperlinks: an LTU information page with internal and external links |
| 4 | `Lab4Task-II.html` | In-page anchor navigation (jump to top/bottom) |
| 5 | `Lab5Task-I.html` | Table with `rowspan` / `colspan` (employee information) |
| 5 | `Lab5Task-II.html` | Nested tables (departments and employees) |
| 5 | `Lab5Task-3.html` | Ordered lists with different numbering styles |

### Graphics (Canvas & SVG)

| Lab | File | Topic |
|-----|------|-------|
| 6 | `Lab6Task-1.html` | Canvas drawing: rectangles, circle, line, text |
| 6 | `Lab6Task-2.html` | Drawing multiple shapes on a canvas |
| 6 | `Lab6Task-3.html` | Interactive canvas: click a shape to change its color |
| 7 | `Lab7Tak-1.html` | Inline SVG icons (home, star, heart) with hover color |
| 7 | `Lab7Task-2.html` | CSS-styled SVG icons with hover scale effect |

### Forms & Icons

| Lab | File | Topic |
|-----|------|-------|
| 8 | `Lab8Task-1.html` | User registration form (text, password, email, radio, checkbox, date, file, select) |
| 8 | `Lab8Task-2.html` | Job application form (select, textarea, file upload) |
| 9 | `Lab9Task-1.html` | Font Awesome icons with hover effect |
| 9 | `Lab9Task-2.html` | Font Awesome icons (brand, user, cart) with hover scale |
| 9 | `Lab9Task-3.html` | Simple styled Font Awesome icons |

### CSS

| Lab | File | Topic |
|-----|------|-------|
| 10 | `Lab10Task-1.html` | CSS priority: inline vs internal vs external |
| 10 | `Lab10Task-2.html` | CSS selectors: universal, element, class, ID, pseudo-class, attribute |
| 11 | `Lab11Task-1.html` | CV as a styled table |
| 11 | `Lab11Task-2.html` | CV using a card-style `div` layout |
| 11 | `Lab11Task-3.html` | College homepage: header, nav bar, main + sidebar (flexbox), footer |
| 12 | `Lab12Task-1.html` | CSS units: `px`, `cm`, `em`, `%`, `vw`/`vh` |
| 12 | `Lab12Task-2.html` | Layout methods: inline, inline-block, float, flexbox, grid |
| 13 | `Lab13.html` | CSS box model (content, padding, border, margin) |
| 14 | `Lab14Task-1.html` | CSS positioning: static, relative, absolute, fixed, sticky |
| 14 | `Lab14Task-2.html` | Responsive design with media queries |
| 15 | `Lab15Task-1.html` | CSS transition (button hover) |
| 15 | `Lab15Task-2.html` | CSS keyframe animation |

### Bootstrap

| Lab | File | Topic |
|-----|------|-------|
| 16 | `Lab16Task-1.html` | Bootstrap 5 setup via CDN with a styled button |
| 16 | `Lab16Task-2.html` | Responsive Bootstrap navbar with collapsible menu |

### JavaScript

| Lab | File | Topic |
|-----|------|-------|
| 17 | `Lab17Task-1.html` | First JavaScript: changing text on button click |
| 18 | `Lab18Task-1.html` | Variables: `var`, `let`, `const` |
| 18 | `Lab18Task-2.html` | Data types: number, string, boolean, object, undefined, null |
| 19 | `Lab19Task-1.html` | Operators: arithmetic, assignment, comparison, logical |
| 19 | `Lab19Task-2.html` | Literals: string, numeric, boolean, object |
| 20 | `Lab20Task-1.html` | Control statements: `if-else`, `switch`, `for`, `while`, `do-while` |
| 20 | `Lab20Task-2.html` | Prime number check |
| 21 | `Lab21Task-1.html` | Defining and calling a function |
| 21 | `Lab21Task-2.html` | Functions with parameters and return values |

---

## Notes

- **Internet connection required** for Labs 9 (Font Awesome 6.4.0) and 16 (Bootstrap 5.3.0), which load from a CDN.
- **Folder structure matters:** `Lab2Task-II.html`, `Lab3Task-I.html`, and `Lab4Task-I.html` use relative paths into `Audio/`, `Video/`, `Files/`, and `Image/`. Keep those folders next to the HTML files or the media will not load.
- Embedded PDFs in Lab 2 may not render in every browser; some download them instead.
- The media files (especially `Video/water.mp4`, about 26 MB) make the repository fairly large. Consider [Git LFS](https://git-lfs.com/) if the repo grows.
- The file `Lab7Tak-1.html` has a typo in its name (should be `Lab7Task-1.html`). It was left unchanged so existing links keep working.

## Technologies

- HTML5
- CSS3
- JavaScript
- Bootstrap 5

## License

This repository contains academic lab work submitted for coursework at Lumbini Technological University.
