# Philomena Marie F. Punzalan | E-Portfolio

Personal portfolio website showcasing my projects, publication work, and skills in software development and data analysis.

**Live site:** [https://phlmnnnnn.github.io](https://phlmnnnnn.github.io/PUNZALAN-E-Portfolio/)

## About

I am a BS Computer Science student (Major in Software Technology) at De La Salle University, expected to graduate in 2028. This site collects my projects, my layout work as a staffer at The LaSallian, and my technical skills.

## Features

- Single-page, responsive layout that works on desktop and mobile
- Light and dark themes, following the system setting with a manual toggle
- Project timeline with tech stacks and short write-ups
- Publications and involvement section
- Skills grouped by category
- Keyboard-friendly navigation and reduced-motion support
- No build step and no dependencies beyond Google Fonts

## Sections

- **Projects:** Webtoon Originals Data Analysis, Computer Laboratory Reservation System, K-pop Merch Transactions Database, Coffee Truck Simulator
- **Publications and involvement:** The LaSallian (Layout Assistant Editor) and the START Program at De La Salle University
- **Skills:** Python, SQL, Java, JavaScript, C, C#, Kotlin, HTML, CSS, and tools
- **Contact:** Email and GitHub

## Tech Stack

- HTML5
- CSS3 (custom properties for theming, flexbox and grid for layout)
- Vanilla JavaScript (theme toggle only)
- Google Fonts: Bricolage Grotesque and Source Serif 4

## Project Structure

```
.
├── index.html     # the whole site: markup, styles, and script
├── resume.pdf     # linked from the "Download resume" button
└── README.md
```


## Run Locally

1. Clone the repository:
   ```
   git clone https://github.com/phlmnnnnn/phlmnnnnn.github.io.git
   ```
2. Open `index.html` in a browser.
3. Optional: serve it with a local server for testing:
   ```
   python -m http.server 8000
   ```
   Then visit http://localhost:8000.

## Customize

- **Text and projects:** edit the sections in `index.html`. Each project is one `<li>` inside the `.timeline` list.
- **Colors:** change the variables under `:root` (light) and the dark theme blocks at the top of the `<style>` section.
- **Fonts:** update the Google Fonts link in `<head>` and the `--display` and `--body` variables.
- **Links:** replace placeholder `#` links (such as "View published issues") with real URLs.

## Contact

- Email: philomena.marie.punzalan@gmail.com
- GitHub: [@phlmnnnnn](https://github.com/phlmnnnnn)

## License
© 2026 Philomena Marie F. Punzalan. All rights reserved. Project descriptions and publication materials may not be reused without permission.
