# `angular-ui-component-library` - the starter for Angular libraries for ui components
References :
> [Read more](https://medium.com/@trekhleb/how-to-create-aot-jit-compatible-angular-4-library-with-external-scss-html-templates-9da6e68dac6e) about architectural **challenges** and **solutions** used in this repository.

# You can use this project to
- create library for **Angular 4**.
- be ready for further **AOT** or **JIT** compilation.
- be ready for further usage **directly in browsers** (let's say [UMD](https://github.com/umdjs/umd) bundle loaded by [SystemJS](https://github.com/systemjs/systemjs)).
- write component styles in **external SCSS files**.
- write component templates in **external HTML files**.
- have **watch-mode** for library builds (including AOT build).

# Main Features
- **AOT/JIT** compatible library build via [Angular Compiler](https://www.npmjs.com/package/@angular/compiler-cli) (ngc).
- **UMD** build via [Webpack](https://webpack.js.org/) that allows you to use your library for browser builds.
- **Documentation hosting**  via [GitHub Pages](https://pages.github.com/).
- **AOT/JIT/UMD demos** via [Webpack](https://webpack.js.org/) and [SystemJS](https://github.com/systemjs/systemjs) that allows you to test library builds.


# Quick Start

```bash
# Clone the repository
git clone https://github.com/budanm/angularuicomponentlibrary

# Go to repository folder
cd angularuicomponentlibrary

# Install all dependencies
npm install

# Build the library
npm run build
```

# File Structure

```
angular-library-seed
  ├─ demo                         * Folder for demo applications (MAY BE DELETED if not required) 
  |  ├─ esm                       * AOT/JIT demo project
  |  ├─ umd                       * UMD demo project
  |  └─ ...                       * More details about this folder may be found in demo folder README file.
  |
  ├─ src                          * Library sources home folder (THE PLACE FOR YOUR LIBRARY SOURCES)
  |  ├─ components                * Example of library components with tests
  |  ├─ services                  * Example of library services with tests
  |  ├─ index.ts                  * Library entry point that is used by builders
  |  └─ tick-tock.module.ts       * Example of library module
  |
  ├─ .editorconfig                * Common IDE configuration
  ├─ .gitignore	                  * List of files that are ignored while publishing to git repo
  ├─ .npmignore                   * List of files that are ignored while publishing to npm
  ├─ LICENSE                      * License details
  ├─ README.md                    * README for you library
  ├─ package.json                 * NPM dependencies, scripts and package configuration
  ├─ tsconfig-aot.json            * TypeScript configuration for AOT build
  └─ webpack-umd.config.ts        * Webpack configuration for building UMD bundle
```
