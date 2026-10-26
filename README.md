# barestrap
Classless, lightweight Bootstrap 6 styling: semantic HTML elements styled with Bootstrap's SASS/CSS variables.

Barestrap `@extend`s Bootstrap's own classes onto HTML elements (e.g. `button` becomes `.btn .btn-styled .btn-solid .theme-primary`). It defines no variables of its own.

```sh
npm install
npm run build   # scss/barestrap.scss -> dist/barestrap.css
```

Open `index.html` for the demo dashboard. Configure it like Bootstrap: `@use "barestrap" with ($enable-shadows: true);`
