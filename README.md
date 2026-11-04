# Portfolio

Personal portfolio for Sara Andersson, software tester and business lawyer.

The whole site is one file: `index.html` (HTML, CSS and JavaScript together, no build step).

## Editing

| What | Where in `index.html` |
| --- | --- |
| Projects shown on the site | `PROJECTS` list near the top of the `<script>` |
| Load repos from GitHub automatically | Set `GITHUB_USER` (e.g. `"sa986-DME"`) |
| Test types in the testing guide | `TYPES` list in the `<script>` |
| CV entries, skills, education | The `CV` section in the HTML |
| Email, GitHub, LinkedIn | The `CONTACT` section in the HTML |
| Colors and fonts | The `:root` block at the top of `<style>` |

To make the "Download CV" button work, add your CV to this repo as `cv.pdf`.

## Publishing

Enable GitHub Pages under **Settings → Pages**: source **Deploy from a branch**, branch `main`, folder `/ (root)`.
The site will then be live at `https://sa986-dme.github.io/portfolio/`.

## Colour palette

| Name | Hex |
| --- | --- |
| Areia (sand) | `#D3C7AD` |
| Verde opaco (olive) | `#6B6751` |
| Terra queimada (burnt earth) | `#754437` |
| Azul (navy) | `#28374A` |
