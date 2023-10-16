# Bootstrap 5 Starter Kit

This is a starter kit for Bootstrap 5 projects. It includes the necessary tools and configurations to help you get started with building web projects using Bootstrap 5.

## Prerequisites

Before you begin, ensure you have the following software installed:

- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/)


## Getting Started

1. Clone or download this repository to your local machine.

2. Install project dependencies by running the following command in the project root directory:

   ```bash
   npm install
   ```

3. Start the development server with live-reloading:

   ```bash
   npm start
   ```

   This will compile Sass files, copy assets and HTML files, and launch a BrowserSync server for live previews.

4. Begin building your project by editing the Sass files and HTML templates in the `src` directory.

## Available Scripts

- `npm run build:sass`: Compile Sass files to CSS and output them in the `public/css` directory.
- `npm run copy:assets`: Copy asset files (e.g., images) to the `public` directory.
- `npm run copy:html`: Copy HTML files to the `public` directory.
- `npm run copy`: Run all copy tasks in parallel.
- `npm run watch:assets`: Watch for changes in asset files and copy them to the `public` directory.
- `npm run watch:html`: Watch for changes in HTML files and copy them to the `public` directory.
- `npm run watch:sass`: Watch for changes in Sass files and recompile to CSS.
- `npm run watch`: Run all watch tasks in parallel.
- `npm run serve`: Start a BrowserSync server for live previews.
- `npm run start`: Run copy, watch, and serve tasks in parallel.
- `npm run build`: Copy HTML files and run build-related tasks.
- `npm run postbuild`: Post-processing tasks (e.g., autoprefixing, minification, and compression).
- `npm run lightningcss`: Use LightningCSS to minify and bundle CSS files.
- `npm run compress`: Gzip compress files in the `public` directory.
- `npm run brotli`: Brotli compress files in the `public` directory.
- `npm run clean`: Clean the `public` directory.

## Dependencies

- [Bootstrap](https://getbootstrap.com/): A popular front-end framework.
- [Popper.js](https://popper.js.org/): Dependency for Bootstrap's dropdowns and tooltips.
- [Sass](https://sass-lang.com/): A CSS preprocessor.
- [BrowserSync](https://www.browsersync.io/): A development server for live-reloading.
- [autoprefixer](https://www.npmjs.com/package/autoprefixer): PostCSS plugin for adding vendor prefixes.
- [copyfiles](https://www.npmjs.com/package/copyfiles): A tool to copy files and directories.
- [lightningcss](https://www.npmjs.com/package/lightningcss): A CSS optimizer and bundler.
- [npm-run-all](https://www.npmjs.com/package/npm-run-all): A CLI tool to run multiple npm scripts in parallel.
- [onchange](https://www.npmjs.com/package/onchange): A tool for running commands when files change.
- [postcss-cli](https://www.npmjs.com/package/postcss-cli): A CLI for PostCSS, a CSS processor.
- [gzipper](https://www.npmjs.com/package/gzipper): A tool for Gzip and Brotli compression.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---