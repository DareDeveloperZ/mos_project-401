# MOS Project 401

**An interactive Mechanics of Solids learning project**

**Project team:** Arnav Jaiswal and Arvind  
**Course Title:** Mechanics of Solids  
**Course Code:** ME2110  
**Faculty:** Prakhar Gupta  
**Project scope:** Ten selected Mechanics of Solids learning modules

## About

MOS Project 401 is a browser-based learning companion designed to connect Mechanics of Solids concepts with visual and numerical experiments. It includes:

- **3D Stress Cube:** edit the six independent components of a symmetric stress matrix and inspect normal/shear arrows and calculated readouts.
- **Traction Explorer:** change the orientation of a plane and calculate traction, normal stress and shear traction.
- **Mohr's Circle:** explore 2D stress transformation, principal stresses and the physical-plane / double-angle relationship.
- **Ten lecture modules:** short explanations, equations, diagrams and worked examples covering the first ten lecture topics.
- **Guided and Challenge modes:** follow prompts or try short numerical questions.
- **About the Project:** team members, scope and technologies are listed inside the site.

## Run the website

This is a static, single-page website. There is no backend, database, account system or build step.

### Option A — Open directly

1. Download or unzip the project folder.
2. Open `index.html` in a recent version of Chrome, Edge or Firefox.
3. Keep an internet connection active so the browser can load Three.js, KaTeX and the web fonts from their CDNs.

### Option B — Run a local web server (recommended)

Open a terminal in this folder and run:

```bash
python -m http.server 8000
```

Then open this address in your browser:

```text
http://localhost:8000
```

Stop the local server with `Ctrl+C` in the terminal.

## Publish it as a website

Because this is a static site, it can be hosted on a static website service. For example, create a repository on GitHub, upload `index.html` and `README.md` to the repository's root, then enable GitHub Pages in the repository settings and publish from the main branch's root folder. The resulting Pages URL can be shared with your evaluator.

Before submission, open the published URL on another device or in a private browser window and verify that the 3D models, controls, lecture navigation and project details all load.

## Technologies

- HTML5
- CSS
- Vanilla JavaScript
- Three.js (3D rendering)
- KaTeX (mathematical typesetting)
- SVG (Mohr's circle and diagrams)

The external libraries and fonts are loaded from public CDNs. An internet connection is needed for the full experience.

## Project notes

- Stress values are displayed in MPa in the main stress interfaces.
- The application uses a tensile-positive convention.
- The interactive stress matrix is constrained to be symmetric.
- The About page identifies the student contributors as **Arnav Jaiswal** and **Arvind**.
- Add your institution, instructor, semester or course section only if your submission format requires them; they have intentionally not been guessed here.
