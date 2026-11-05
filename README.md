# Darshan Gaikwad — Portfolio

A responsive personal portfolio built with plain HTML, CSS, and JavaScript. The portfolio highlights Darshan's engineering studies, technical skills, projects, training, and achievements. Details and dates are based on the supplied resume; the IoT internship date was not listed there.

## Project structure

```text
portfolio/
├── index.html
├── style.css
├── script.js
├── images/
│   └── profile-placeholder.svg
└── resume.pdf
```

## Run locally

Open `index.html` in a browser. For local development, you can also serve the folder with Python:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customize

- Replace `images/profile-placeholder.svg` with a profile image and update its `<img>` source in `index.html` if you use a different file.
- `resume.pdf` is the supplied resume and is linked from the Download Resume button.
- Update the contact details and LinkedIn address in `index.html` if they change. A GitHub profile URL was not included in the provided information, so the footer shows its icon without linking to an unverified profile.
- The contact form uses `mailto:` to prepare a message in the visitor's email application; it does not submit data to a server.

## Accessibility and responsive layout

The site uses semantic sections, keyboard-visible focus states, an accessible mobile navigation toggle, reduced-motion support, and responsive CSS Grid and Flexbox layouts.
