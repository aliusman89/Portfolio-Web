# Ali Usman Tahir — Personal Portfolio

Personal portfolio website for **CS344: Web Engineering — Lab 3 (HTML
Advanced: Personal Portfolio II)**, built with plain HTML and CSS only
(no JavaScript, no CSS frameworks).

## Live Site
Live link (after deploying via GitHub Pages):
`https://aliusman89.github.io/Portfolio-Web/`

## Pages
| File | Description |
|---|---|
| `index.html` | Home / About — bio, quick facts, PakOS highlight |
| `skills.html` | Technical stack, core strengths, languages |
| `gallery.html` | Project gallery (6 images, floated grid) |
| `hobbies.html` | Event leadership and research interests |
| `contact.html` | Contact details and a static contact form |

## Folder Structure
```
portfolio/
├── index.html
├── hobbies.html
├── contact.html
├── gallery.html
├── skills.html
├── css/
│   └── style.css
├── images/
│   ├── avatar.jpg
│   ├── hobbies-banner.jpg
│   ├── skills-banner.jpg
│   ├── photo1.jpg ... photo6.jpg
└── README.md
```

## Techniques Used
- Single external stylesheet (`css/style.css`) — no inline styles.
- Horizontal navigation menu built with `float: left` on list items.
- Bio sections use `float` to place an image beside text, cleared with
  a `.clearfix` class.
- Image gallery arranged with `float: left` on gallery items and a
  clearfix on the container.
- Fully responsive: floats collapse to a stacked layout under 700px
  via a media query.

## Deployment (GitHub Pages)
1. `git init`
2. `git add .`
3. `git commit -m "Initial portfolio commit"`
4. `git remote add origin https://github.com/aliusman89/Portfolio-Web`
5. `git push -u origin main`
6. On GitHub: **Settings → Pages → Source: main branch → Save**
7. Live site will be available at `https://<username>.github.io/portfolio/`

## Author
Ali Usman Tahir — Software Engineering Student, NUST SEECS
