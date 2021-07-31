# Notes Garden HTML generator

This repo was used to create the initial HTMLs for https://github.com/Jekyll-Garden/jekyll-garden.github.io. Read that readme for more details.

### Development
```sh
cd my-bulma-project
npm install
npm start
```

Open `build/index.html` in your browser.
As long as `npm start` is running, it will **watch** your changes. You can edit files under `src/_sass` and `src/_javascript` folder at will. Changes are **immediately** compiled to their destinations, where `build/index.html` will pick them up upon reload in your browser.

Some controlling output is written to the `npm start` console in that process:

```sh
_javascript/main.js -> build/lib/main.js

=> changed: $HOME/projects/start-with-bulma/_sass/main.scss
Rendering Complete, saving .css file...
Wrote CSS to $HOME/projects/start-with-bulma/css/main.css
```

Use `npm run` to show all available commands:


If you want to learn more, follow these links: [Bulma homepage](http://bulma.io) and [Documentation](http://bulma.io/documentation/overview/start/).