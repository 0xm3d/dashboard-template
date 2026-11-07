# Dashboard Template

A responsive, multi-page dashboard interface built with HTML and CSS. It includes a dashboard overview, account settings, profile, projects, courses, friends, files, and subscription plans.

## Pages

| Page | File |
| --- | --- |
| Dashboard | [index.html](./index.html) |
| Settings | [settings.html](./settings.html) |
| Profile | [profile.html](./profile.html) |
| Projects | [projects.html](./projects.html) |
| Courses | [courses.html](./courses.html) |
| Friends | [friends.html](./friends.html) |
| Files | [files.html](./files.html) |
| Plans | [plans.html](./plans.html) |

## Run locally

There is no build step or package installation required. From the project root, start a local static server:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser. You can also open `index.html` directly, though using a local server is recommended.

## Built with

- HTML5 and CSS3
- A custom CSS utility framework in `css/framework.css`
- Page layouts and responsive styles in `css/main.css`
- Font Awesome icons, with styles in `css/all.min.css` and font files in `webfonts/`
- Open Sans from Google Fonts (requires an internet connection to load)

## Project structure

```text
.
├── index.html
├── settings.html
├── profile.html
├── projects.html
├── courses.html
├── friends.html
├── files.html
├── plans.html
├── css/
│   ├── all.min.css
│   ├── framework.css
│   └── main.css
├── images/
└── webfonts/
```

## Customization

- Edit the HTML files to change page content.
- Update shared utilities in `css/framework.css` and page-specific layout or responsive rules in `css/main.css`.
- Replace or add image assets in `images/`.

This is a static UI template; it does not include a backend, data persistence, or JavaScript-powered interactions.
