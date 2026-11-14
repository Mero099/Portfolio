# Marwan Malik — Portfolio

A responsive portfolio built with React and Vite.

## Project structure

```text
src/
  components/       Page sections and their colocated styles
    About/
    Contact/
    Home/
    InteractiveLab/
    Navbar/
    Projects/
  data/             Editable portfolio content and site settings
  App.jsx            Page composition and footer
  App.css            Global styles and footer styles
public/
  MARWAN-MALIK-CV.pdf
images/              Source images and original CV
```

## Updating content

- Edit your name, role, email address, and CV download path in `src/data/site.js`.
- Update the hero metrics and technology list in `src/data/home.js`.
- Edit capability cards in `src/data/capabilities.js`.
- Edit project cards in `src/data/selectedWork.js`.
- Edit the interactive layout options and workflow in `src/data/interactiveLab.js`.
- Update section presentation in the CSS file alongside its component.

## Development

```sh
npm install
npm run dev
```

Run the production build and lint checks with:

```sh
npm run build
npm run lint
```
