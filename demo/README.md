# `angular-ui-component-library` demo projects

> This folder contains two demo-projects (`esm` and `umd` folders) for [angular-library-seed](https://github.com/trekhleb/angular-library-seed). These demo projects may help you to test whether your library supports AOT/JIT/UMD builds or not.
>
> - `esm` folder contains Angular project that is built using [@angular/compiler](https://www.npmjs.com/package/@angular/compiler) and [Webpack](https://webpack.js.org/). This demo project utilizes ESM (pure ES2015) sources of your library to do two kind of compilations:
>   - [AOT](https://angular.io/docs/ts/latest/cookbook/aot-compiler.html) (ahead-of-time) compilation.
>   - [JIT](https://angular.io/docs/ts/latest/cookbook/aot-compiler.html) (just-in-time) compilation.
>
> - `umd` folder contains Angular project that is being built and assembled in browser by [SystemJS](https://github.com/systemjs/systemjs). This demo project utilizes [UMD](https://github.com/umdjs/umd) bundle of your library.

Demo-projects are created as an alternative to `npm link` command. You may simply delete this `demo` folder if you prefer to use [yarn link](https://yarnpkg.com/en/docs/cli/link) instead to check how your library is being built.
