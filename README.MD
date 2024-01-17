# PWA boilerplate

Easy ready-to-use boilerplate based on AlpineJS, Vite and SASS.

## Included tools and libraries

- **Task runner** : [Vite](https://vitejs.dev/), for easy build and deploy. Ultra-fast and easy setup on Netlify.
- **Javascript framework** : [AlpineJS](https://alpinejs.dev/), as a lightweight and modern JS library. Perfect replacement for jQuery, provides data-binding and other powerful features.
- **Post-processor** : [SASS](https://sass-lang.com/), the full-featured CSS post-processor everyone loves.

## Code structure

This boilerplate is intended for crafting a lightweight single-page Progressive Web App, not for a full-fledged application.<br/>
Big frameworks like Next/Nuxt are best suited for complex applications.

### Javascript

- `/main.js` is the Javascript boostrap file with SASS and AlpineJS imports and initialization.
- `/src/js/app.js` is the App's main function.
- `/data/` holds static data, like translations or collections. An example `i18n.js` file is provided. 

### HTML

`/index.html`is the HTML boostrap file, with Alpine App() declaration and templates.

### CSS

SASS files can be found in the `/src/scss/` folder.

### Static assets

All static assets like images or fonts are stored in the `/public/` folder.

### Tooling

- `.node-version` automatically sets the NodeJS version to be used within the project if `nvm`and `avn` are already installed.

## Usage

### Local dev

    npm run dev

### Build for deploy

    npm run build

Output can be found in `/dist` and deployed as static anywhere.


## Useful librairies and tools tested

### Design Systems

#### Bulma ([https://bulma.io/](https://bulma.io/))

Lightweight and modern CSS design system.
Install with `npm install bulma --save` and import into `main.js`

