---
title: Awesome webpack
sort: 2
contributors:
  - snitin315
---

A curated list of awesome webpack resources, libraries, tools and applications. It is inspired by the [awesome](https://github.com/sindresorhus/awesome) list. Feel free to improve this list by contributing.

## Webpack Ecosystem

**Remember to** [Cast your vote for upcoming Webpack features!](https://webpack.js.org/vote/)

### Support Webpack

- [Webpack Open Collective](https://opencollective.com/webpack) - Help support the teams ongoing development efforts.

### Community

- [StackOverflow](http://stackoverflow.com/tags/webpack)
- [Medium](https://medium.com/tag/webpack)
- [Gitter Chat](https://gitter.im/webpack/webpack)

### Twitter

_People passionate about Webpack (In no particular order)_

- [Sean T. Larkin - @TheLarkInn](https://twitter.com/TheLarkInn) TPM at [Microsoft](https://twitter.com/MSEdgeDev). Developer Advocate and webpack core team member.
- [Juho Vepsäläinen - @bebraw](https://twitter.com/bebraw) from [SurviveJS](https://twitter.com/survivejs) and webpack core team member.
- [Eric Clemmons - @ericclemmons](https://twitter.com/ericclemmons) VP of Software Development at [HigherEdHQ](https://twitter.com/HigherEdHQ). Webpack member.
- [Patrick Stapleton - @gdi2290](https://twitter.com/gdi2290) from [AngularClass](https://angularclass.com), [AngularAir](https://angularair.com) and [Angular Universal](https://github.com/angular/universal). Webpack member.
- [Kent C. Dodds - @kentcdodds](https://twitter.com/kentcdodds) from [PayPal Engineering](https://twitter.com/PayPalEng) and [JavaScript Air](https://twitter.com/JavaScriptAir). Webpack member.
- [Johannes Ewald - @Jhnnns](https://twitter.com/Jhnnns): Webpack core team member.
- [Joshua Wiens - @d3viant0ne](https://twitter.com/d3viant0ne): Technical Lead for [EasyMetrics](https://easymetrics.com). Webpack member.
- [Jonathan Creamer - @jcreamer898](https://twitter.com/jcreamer898): Microsoft MVP and [Telerik](https://github.com/telerik) Developer Expert.
- [Kees Kluskens - @keeskluskens](https://twitter.com/keeskluskens): - Software Engineer at [Code Yellow](https://codeyellow.nl), Webpack core team member.

## Libraries

### Loaders

#### File Type

- [HTML Loader](https://github.com/webpack/html-loader): HTML loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Responsive Loader](https://github.com/herrstucki/responsive-loader): Loader for responsive images. -- _Maintainer_: `Jeremy Stucki` [![Github][githubicon]](https://github.com/herrstucki)
- [SVG Url Loader](https://github.com/bhovhannes/svg-url-loader): Loader which loads SVG file as utf-8 encoded Url. -- _Maintainer_: `Hovhannes Babayan` [![Github][githubicon]](https://github.com/bhovhannes)
- [mermaid Loader](https://github.com/popul/mermaid-loader): [mermaid](https://github.com/mermaid-js/mermaid) loader module (diagrams) for Webpack. -- _Maintainer_: `Paul Musso` [![Github][githubicon]](https://github.com/popul)
- [wasm loader](https://github.com/ballercat/wasm-loader): wasm binary loader module for Webpack. -- _Maintainer_: `Arthur Buldauskas` [![Github][githubicon]](https://github.com/ballercat)
- [Imagemin Loader/Plugin](https://github.com/itgalaxy/imagemin-webpack): Image minimizing loader + plugin for webpack. -- _Maintainer_: `itgalaxy inc.` [![Github][githubicon]](https://github.com/itgalaxy)
- [Bin Exec Loader](https://github.com/milewski/bin-exec-loader): Pipe any file through any binary. -- _Maintainer_: `Rafael Milewski` [![Github][githubicon]](https://github.com/milewski)
- [GraphQL Loader](https://github.com/stephen/graphql-loader): `.graphql` document loader. -- _Maintainer_: `Stephen Wan` [![Github][githubicon]](https://github.com/stephen)

#### Component & Template

- [Angular2 Template Loader](https://github.com/TheLarkInn/angular2-template-loader): Inlines html and style's in Angular2 components. -- _Maintainer_: `Sean Larkin` [![Github][githubicon]](https://github.com/TheLarkInn) [![Twitter][twittericon]](https://twitter.com/TheLarkInn)
- [Handlebars Loader](https://github.com/pcardune/handlebars-loader): A handlebars template loader for Webpack. -- _Maintainer_: `Paul Carduner` [![Github][githubicon]](https://github.com/pcardune) [![Twitter][twittericon]](https://twitter.com/pcardune)
- [Vue Loader](https://github.com/vuejs/vue-loader): Webpack loader for Vue.js components. -- _Maintainer_: `Vuejs Team` [![Github][githubicon]](https://github.com/vuejs) [![Twitter][twittericon]](https://twitter.com/vuejs)
- [SVG React Loader](https://github.com/jhamlet/svg-react-loader) - Webpack SVG to React Component Loader. -- _Maintainer_: `Jerry Hamlet` [![Github][githubicon]](https://github.com/jhamlet) [![Twitter][twittericon]](https://twitter.com/jerryhamlet)
- [Underscore Loader](https://github.com/emaphp/underscore-template-loader) - Underscore and Lodash template loader. -- _Maintainer_: `Emmanuel Antico` [![Github][githubicon]](https://github.com/emaphp) [![Twitter][twittericon]](https://twitter.com/emaphp)
- [ngTemplate Loader](https://github.com/WearyMonkey/ngtemplate-loader) - Angular1 Template Loader. -- _Maintainer_: `Toby Rahilly` [![Github][githubicon]](https://github.com/WearyMonkey)
- [ngInlineStylesLoader](https://github.com/seveves/ng-inline-styles-loader): Optimizes inlined css of angular components. -- _Maintainer_: `Severin Friede` [![Github][githubicon]](https://github.com/seveves)
- [Markup-inline Loader](https://github.com/asnowwolf/markup-inline-loader) Inline SVGs to HTML -- _Maintainer_: `Zhicheng Wang` [![Github][githubicon]](https://github.com/asnowwolf)
- [Polymer Loader](https://github.com/webpack-contrib/polymer-webpack-loader) - Loader for Polymer elements. -- _Maintainers_: `Rob Dodson` [![Github][githubicon]](https://github.com/robdodson) - `Chad Killingsworth` [![Github][githubicon]](https://github.com/ChadKillingsworth) - `Bryan Coulter` [![Github][githubicon]](https://github.com/bryandcoulter)
- [Tag Loader](https://github.com/riot/tag-loader) - Loader for Riot tag files. -- _Maintainer_: `Riot Team` [![Github][githubicon]](https://github.com/riot) [![Twitter][twittericon]](https://twitter.com/riotjs_)
- [Twig Loader](https://github.com/zimmo-be/twig-loader) - Twig template loader. -- _Maintainer_: `Zimmo.be Team` [![Github][githubicon]](https://github.com/zimmo-be)
- [Auto ngTemplate Loader](https://github.com/YashdalfTheGray/auto-ngtemplate-loader): Autodetect Angular 1 templates and load them. -- _Maintainer_: `Yash Kulshrestha` [![Github][githubicon]](https://github.com/YashdalfTheGray)
- [Pug Loader](https://github.com/pugjs/pug-loader) - Pug template loader (formerly Jade). -- _Maintainer_: `Pug Team` [![Github][githubicon]](https://github.com/pugjs)
- [Simple Nunjucks Loader](https://github.com/ogonkov/nunjucks-loader) - Nunjucks template loader. -- _Maintainer_: `ogonkov` [![Github][githubicon]](https://github.com/ogonkov)

#### Styles

- [Style Loader](https://github.com/webpack/style-loader): Style loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [PostCSS Loader](https://github.com/postcss/postcss-loader): PostCSS loader for Webpack. -- _Maintainer_: `PostCSS Team` [![Github][githubicon]](https://github.com/postcss) [![Twitter][twittericon]](https://twitter.com/PostCSS)
- [CSS Loader](https://github.com/webpack/css-loader): CSS loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [SASS Loader](https://github.com/jtangelder/sass-loader): SASS loader for Webpack. -- _Maintainer_: `Jorik Tangelder` [![Github][githubicon]](https://github.com/jtangelder) [![Twitter][twittericon]](https://twitter.com/jorikdelaporik)
- [Less Loader](https://github.com/webpack/less-loader): Less loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Stylus Loader](https://github.com/shama/stylus-loader): A stylus loader for webpack. -- _Maintainer_: `Kyle Robinson Young` [![Github][githubicon]](https://github.com/shama) [![Twitter][twittericon]](https://twitter.com/shamakry)
- [Isomorphic Style Loader](https://github.com/kriasoft/isomorphic-style-loader): Isomorphic CSS style loader for Webpack. -- _Maintainer_: `Kriasoft Team` [![Github][githubicon]](https://github.com/kriasoft) [![Twitter][twittericon]](https://twitter.com/kriasoft)
- [Minify CSS-in-JS Loader](https://github.com/zaaack/minify-cssinjs-loader): RegExp-based minify CSS-in-JS loader for Webpack, don't need babel. -- _Maintainer_: `Zack Young` [![Github][githubicon]](https://github.com/zaaack) [![Twitter][twittericon]](https://twitter.com/ZaaackYoung)
- [SASS Resources Loader](https://github.com/shakacode/sass-resources-loader): Globally import SASS resources (variables, mixins, etc.). -- _Maintainer_: `ShakaCode` [![Github][githubicon]](https://github.com/shakacode) [![Twitter][twittericon]](https://twitter.com/shakacode)

#### Language & Framework

- [TS Loader](https://github.com/TypeStrong/ts-loader): TypeScript loader for webpack. -- _Maintainer_: `TypeStrong Team` [![Github][githubicon]](https://github.com/TypeStrong)
- [Coffee Loader](https://github.com/webpack/coffee-loader): Coffee loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Bootstrap Loader](https://github.com/shakacode/bootstrap-loader): Load Bootstrap styles in your Webpack bundle. -- _Maintainer_: `ShakaCode Team` [![Github][githubicon]](https://github.com/shakacode) [![Twitter][twittericon]](https://twitter.com/shakacode)
- [PostHTML Loader](https://github.com/posthtml/posthtml-loader): PostHTML loader for Webpack. -- _Maintainer_: `PostHTML Team` [![Github][githubicon]](https://github.com/posthtml) [![Twitter][twittericon]](https://twitter.com/PostHTML)
- [ELM Loader](https://github.com/rtfeldman/elm-webpack-loader): Webpack loader for the Elm programming language. -- _Maintainer_: `Richard Feldman` [![Github][githubicon]](https://github.com/rtfeldman) [![Twitter][twittericon]](https://twitter.com/rtfeldman)
- [Fengari Loader](https://github.com/fengari-lua/fengari-loader/): Run Lua code using [Fengari](https://fengari.io). -- _Maintainer_: `Daurnimator` [![Github][githubicon]](https://github.com/daurnimator) [![Twitter][twittericon]](https://twitter.com/daurnimator)

#### Utility

- [Babel Loader](https://github.com/babel/babel-loader): Webpack plugin for Babel. -- _Maintainer_: `Babel Team` [![Github][githubicon]](https://github.com/babel) [![Twitter][twittericon]](https://twitter.com/babel)
- [Worker Loader](https://github.com/webpack/worker-loader): Worker loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Resolve URL Loader](https://github.com/bholloway/resolve-url-loader): Resolves relative paths in url() statements. -- _Maintainer_: `Ben Holloway` [![Github][githubicon]](https://github.com/bholloway)
- [Import Loader](https://github.com/webpack/imports-loader): Imports loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [SourceMap Loader](https://github.com/webpack/source-map-loader): Extract sourceMappingURL comments from modules. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Combine Loader](https://www.npmjs.com/package/webpack-combine-loaders) - Converts a loaders array into a single loader string. -- _Maintainer_: `James Friend` [![Github][githubicon]](https://github.com/jsdf)
- [Icon Font Loader](https://github.com/vusion/icon-font-loader) - Converts svgs into font icons in CSS. -- _Maintainer_: `Forrest R. Zhao` [![Github][githubicon]](https://github.com/rainfore)
- [Icons Loader](https://www.npmjs.com/package/icons-loader) - Generates an iconfont from SVG dependencies. -- _Maintainer_: `Mike Vercoelen` [![Github][githubicon]](https://github.com/mikevercoelen)
- [Modernizr Loader](https://www.npmjs.com/package/modernizr-loader) - Get your modernizr build bundled with webpack. -- _Maintainer_: `Peerigon Devs` [![Github][githubicon]](https://github.com/peerigon)
- [ngRouter Loader](https://github.com/shlomiassaf/ng-router-loader) - AOT capable NgModule lazy loading using angular router -- _Maintainer_: `Shlomi Assaf` [![Github][githubicon]](https://github.com/shlomiassaf) [![Twitter][twittericon]](https://twitter.com/shlomiassaf)
- [Lingui Loader](https://github.com/lingui/js-lingui/tree/master/packages/loader) - Compile message catalogs on the fly for jsLingui, i18n library -- _Maintainer_: `Tomáš Ehrlich` [![Github][githubicon]](https://github.com/tricoder42) [![Twitter][twittericon]](https://twitter.com/tomas_ehrlich)
- [Shell Loader](https://github.com/localjo/shell-loader) - Run an arbitrary shell script on source files. -- _Maintainer_: `Jo Sprague` [![Github][githubicon]](https://github.com/localjo)
- [EXIF Loader](https://github.com/herschel666/exif-loader) - Extract EXIF- & IPTC-data from your JPGs during build-time. -- _Maintainer_: `Emanuel Kluge` [![Github][githubicon]](https://github.com/herschel666/exif-loader) [![Twitter][twittericon]](https://twitter.com/herschel_r)
- [esbuild Loader](https://github.com/privatenumber/esbuild-loader) - Blazing fast alternative to babel-loader, ts-loader, and Terser powered by [esbuild](https://github.com/evanw/esbuild). -- _Maintainer_: `Hiroki Osame` [![Github][githubicon]](https://github.com/privatenumber/esbuild-loader) [![Twitter][twittericon]](https://twitter.com/privatenumbr)

#### Testing

- [Karma Webpack](https://github.com/webpack/karma-webpack): Use Karma with Webpack. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Istanbul Webpack plugin](https://github.com/DxCx/webpack-istanbul-plugin): Use Istanbul instrumenter for the whole pack. -- _Maintainer_: `Hagai Cohen` [![Github][githubicon]](https://github.com/DxCx)

### Integration Libraries

- [Dotenv Webpack](https://github.com/mrsteele/dotenv-webpack): Compiles environment variables into your bundle via dotenv. -- _Maintainer_: `Matthew Steele` [![Github][githubicon]](https://github.com/mrsteele) [![Twitter][twittericon]](https://twitter.com/Matt_R_Steele)
- [Terse Webpack](https://github.com/ericclemmons/terse-webpack) - Webpack simplified in a fluent API with presets. -- _Maintainer_: `Eric Clemmons` [![Github][githubicon]](https://github.com/ericclemmons) [![Twitter][twittericon]](https://twitter.com/ericclemmons)
- [SystemJS Webpack](https://github.com/guybedford/systemjs-webpack-plugin) - Webpack bundling for SystemJS. -- _Maintainer_: `Guy Bedford` [![Github][githubicon]](https://github.com/guybedford) [![Twitter][twittericon]](https://twitter.com/guybedford)
- [Gulp Webpack Stream](https://github.com/shama/webpack-stream) - Run webpack through a stream interface. -- _Maintainer_: `Kyle Robinson Young` [![Github][githubicon]](https://github.com/shama) [![Twitter][twittericon]](https://twitter.com/shamakry)
- [Webpack Blocks](https://github.com/andywer/webpack-blocks) - Configure webpack using functional feature blocks. -- _Maintainer_: `Andy Wermke` [![Github][githubicon]](https://github.com/andywer) [![Twitter][twittericon]](https://twitter.com/andywritescode)
- [Webpacker](https://github.com/rails/webpacker) - Offical webpack gem for integration into ruby on rails projects. -- _Maintainer_: `Rails` [![Github][githubicon]](https://github.com/rails)
- [WebpackAspnetMiddleware](https://github.com/frankwallis/WebpackAspnetMiddleware) - Development middleware for ASP.NET 5. -- _Maintainer_: `Frank Wallis` [![Github][githubicon]](https://github.com/frankwallis)
- [Consul Key/Value Webpack](https://github.com/marlonmleite/consul-env-webpack-plugin): Compiles environment variables into your bundle via [Consul KV-store](https://www.consul.io/api/kv.html). -- _Maintainer_: `Marlon Maxwel` [![Github][githubicon]](https://github.com/marlonmleite)

### Webpack Plugins

- [DefinePlugin](https://webpack.js.org/plugins/define-plugin/): Create global constants which can be configured at compile time. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Compression Plugin](https://github.com/webpack/compression-webpack-plugin): Prepare assets to serve with Content-Encoding. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Offline Plugin](https://github.com/NekR/offline-plugin): Offline plugin (ServiceWorker, AppCache) for Webpack. -- _Maintainer_: `Arthur Stolyar` [![Github][githubicon]](https://github.com/NekR) [![Twitter][twittericon]](https://twitter.com/nekrtemplar)
- [Rewire Plugin](https://github.com/jhnns/rewire-webpack): Dependency injection for Webpack bundles. -- _Maintainer_: `Johannes Ewald` [![Github][githubicon]](https://github.com/jhnns) [![Twitter][twittericon]](https://twitter.com/Jhnnns)
- [HTML Webpack Plugin](https://github.com/ampedandwired/html-webpack-plugin): Simplifies creation of HTML files. -- _Maintainer_: `Jan Nicklas` [![Github][githubicon]](https://github.com/jantimon) [![Twitter][twittericon]](https://twitter.com/jantimon)
- [Copy Webpack Plugin](https://github.com/kevlened/copy-webpack-plugin): Copy files and directories in webpack. -- _Maintainer_: `Len Boyette` [![Github][githubicon]](https://github.com/kevlened) [![Twitter][twittericon]](https://twitter.com/kevlened)
- [Split By Path](https://github.com/BohdanTkachenko/webpack-split-by-path): Split By Path Webpack Plugin. -- _Maintainer_: `Bohdan Tkachenko` [![Github][githubicon]](https://github.com/BohdanTkachenko) [![Twitter][twittericon]](https://twitter.com/bohdantkachenko)
- [SW Precache](https://github.com/goldhand/sw-precache-webpack-plugin) - Generates a service worker to precache bundle. -- _Maintainer_: `Will Farley` [![Github][githubicon]](https://github.com/goldhand)
- [CoreJS Plugin](https://github.com/gdi2290/core-js-webpack-plugin) - Core-JS as a webpack plugin. -- _Maintainer_: `PatrickJS` [![Github][githubicon]](https://github.com/gdi2290)
- [Bundle Analyzer](https://github.com/th0r/webpack-bundle-analyzer) - Utility that represents bundles as an interactive treemap. -- _Maintainer_: `Yuriy Grunin` [![Github][githubicon]](https://github.com/th0r)
- [Module Mapping](https://github.com/spartez/module-mapping-webpack-plugin) - Maps modules onto different files. -- _Maintainer_: `Spartez Team` [![Github][githubicon]](https://github.com/spartez) [![Twitter][twittericon]](https://twitter.com/thisisspartez)
- [Serverless Webpack](https://github.com/elastic-coders/serverless-webpack) - Serverless plugin to bundle your lambdas. -- _Maintainer_: `Elastic Coders` [![Github][githubicon]](https://github.com/elastic-coders) [![Twitter][twittericon]](https://twitter.com/ElasticCoders)
- [Prerender SPA](https://github.com/chrisvfritz/prerender-spa-plugin) - Framework-agnostic static site generation for SPAs. -- _Maintainer_: `Chris Fritz` [![Github][githubicon]](https://github.com/chrisvfritz) [![Twitter][twittericon]](https://twitter.com/chrisvfritz)
- [Static Site Generator Plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) - Minimal, unopinionated static site generator. -- _Maintainer_: `Mark Dalgleish` [![Github][githubicon]](https://github.com/markdalgleish)
- [SVG Sprite Plugin](https://github.com/TodayTix/svg-sprite-webpack-plugin) - Plugin for SVG sprites and icons. -- _Maintainer_: `Jeremy Tice` ([`TodayTix`](https://github.com/TodayTix)) [![Github][githubicon]](https://github.com/jetpacmonkey) [![Twitter][twittericon]](https://twitter.com/jetpacmonkey)
- [Imagemin Webpack Plugin](https://github.com/Klathmon/imagemin-webpack-plugin) - Minify images with Imagemin. -- _Maintainer_: `Gregory Benner` [![Github][githubicon]](https://github.com/Klathmon) [![Twitter][twittericon]](https://twitter.com/Klathmon)
- [Prepack Webpack Plugin](https://github.com/gajus/prepack-webpack-plugin) - A webpack plugin for prepack. -- _Maintainer_: `Gajus Kuizinas` [![Github][githubicon]](https://github.com/gajus)
- [Modules CDN Webpack Plugin](https://github.com/mastilver/modules-cdn-webpack-plugin) - Dynamically load your modules from a CDN. -- _Maintainer_: `Thomas Sileghem` [![Github][githubicon]](https://github.com/mastilver)
- [Generate package.json Plugin](https://github.com/lostpebble/generate-package-json-webpack-plugin) - Limit dependencies in a deployment `package.json` to only those that are actually being used by your bundle. -- _Maintainer_: `Paul Myburgh` [![Github][githubicon]](https://github.com/lostpebble)
- [Progressive Web App Manifest](https://github.com/arthurbergmz/webpack-pwa-manifest) - PWA manifest manager and generator. -- _Maintainer_: `Arthur A. Bergamaschi` [![Github][githubicon]](https://github.com/arthurbergmz)
- [FileManager Webpack Plugin](https://github.com/gregnb/filemanager-webpack-plugin) - Copy, move, delete files and directories before and after Webpack builds -- _Maintainer_: `Gregory Nowakowski` [![Github][githubicon]](https://github.com/gregnb)
- [Fork TS Checker Webpack Plugin](https://github.com/TypeStrong/fork-ts-checker-webpack-plugin) - Webpack plugin that runs typescript type checker on a separate process. -- _Maintainer_: `TypeStrong Team` [![Github][githubicon]](https://github.com/TypeStrong)
- [Duplicate Package Checker Webpack Plugin](https://github.com/darrenscerri/duplicate-package-checker-webpack-plugin) - Warns you when multiple versions of the same package exist in your bundle -- _Maintainer_: `Darren Scerri` [![Github][githubicon]](https://github.com/darrenscerri)
- [Circular Dependency Plugin](https://github.com/aackerman/circular-dependency-plugin) - Detect modules with circular dependencies when bundling -- _Maintainer_: `Aaron Ackerman` [![Github][githubicon]](https://github.com/aackerman)
- [webpack-inject-plugin](https://github.com/adierkens/webpack-inject-plugin) - A webpack plugin to dynamically inject code into the bundle. -- _Maintainer_: `Adam Dierkens` [![Github][githubicon]](https://github.com/adierkens)
- [Public Path Manipulation Plugin](https://github.com/agoldis/webpack-require-from) - control `publicPath` of dynamically loaded resources at runtime -- _Maintainer_: `Andrew Goldis` [![Github][githubicon]](https://github.com/agoldis)
- [Build Notifier Plugin](https://github.com/roccoc/webpack-build-notifier) - Display OS-level notifications for build errors and warnings. -- _Maintainer_: `Rocco Cataldo` [![Github][githubicon]](https://github.com/roccoc)
- [CSS Cleanup Webpack Plugin](https://github.com/do-web/css-cleanup-webpack-plugin) - A plugin to remove duplicated and unused css rules -- _Maintainer_: `Dominik Weber` [![Github][githubicon]](https://github.com/do-web)
- [Extension Reloader](https://github.com/rubenspgcavalcante/webpack-extension-reloader) - Hot reloading while developing browser extensions -- _Maintainer_: `Rubens P. G. Cavalcante` [![Github][githubicon]](https://github.com/rubenspgcavalcante) [![Twitter][twittericon]](https://twitter.com/rubenspgc)
- [Htmls Webpack Plugin](https://github.com/zaaack/htmls-webpack-plugin): Simple and fast multiple-htmls-generating plugin for webpack. -- _Maintainer_: `Zack Young` [![Github][githubicon]](https://github.com/zaaack) [![Twitter][twittericon]](https://twitter.com/ZaaackYoung)
- [Mini css extract plugin](https://github.com/webpack-contrib/mini-css-extract-plugin):
  Lightweight CSS extraction plugin -- _Maintainer_: `Webpack Contrib` [![Github][githubicon]](https://github.com/webpack-contrib)
- [build-hash-webpack-plugin](https://github.com/Cosium/build-hash-webpack-plugin) For each build, Webpack generates an in-memory hash allowing to know if two build outputs are the same or not. This plugin writes the described build hash in a separate json file. -- _Maintainer_: `Réda Housni Alaoui` [![Github][githubicon]](https://github.com/reda-alaoui) [![Twitter][twittericon]](https://twitter.com/alaouirda)
- [webpack-hook-plugin](https://github.com/tienne/webpack-hook-plugin) - run any shell commands before or after webpack builds -- _Maintainer_: `David Kwon` [![Github][githubicon]](https://github.com/tienne)
- [Dynamic Vendor Webpack Plugin](https://github.com/bios21/dynamic-vendor-webpack-plugin) - Gives you a way to import vendors with dynamic variable and specific code splitting. -- _Maintainer_ `Lilian Saget-Lethias` [![Github][githubicon]](https://github.com/bios21) [![Twitter][twittericon]](https://twitter.com/lsagetlethias)
- [Define Variable Webpack Plugin](https://github.com/bios21/define-variable-webpack-plugin) - Enhancement of DefinePlugin to store defined things in actual variables. -- _Maintainer_ `Lilian Saget-Lethias` [![Github][githubicon]](https://github.com/bios21) [![Twitter][twittericon]](https://twitter.com/lsagetlethias)
- [Shell Script Webpack Plugin](https://github.com/drewloomer/hook-shell-script-webpack-plugin) - A plugin for running arbitrary shell scripts when [compiler hooks](https://webpack.js.org/api/compiler-hooks/) are triggered. -- _Maintainer_ `Drew Loomer` [![Github][githubicon]](https://github.com/drewloomer) [![Twitter][twittericon]](https://twitter.com/drewloomer)
- [Stylelint Webpack Plugin](https://github.com/webpack-contrib/stylelint-webpack-plugin): A Stylelint plugin for webpack. -- _Maintainer_: `Ricardo Gobbo de Souza` [![Github][githubicon]](https://github.com/ricardogobbosouza)
- [ESLint Webpack Plugin](https://github.com/webpack-contrib/eslint-webpack-plugin): A ESLint plugin for webpack
  . -- _Maintainer_: `Ricardo Gobbo de Souza` [![Github][githubicon]](https://github.com/ricardogobbosouza)
- [Exclude Assets Webpack Plugin](https://github.com/klaytonfaria/webpack-exclude-assets-plugin): A plugin to exclude assets from webpack output based on a path RegExp pattern. -- _Maintainer_: `Klayton Faria` [![Github][githubicon]](https://github.com/klaytonfaria)
- [Webpack Shell Plugin Next](https://github.com/s00d/webpack-shell-plugin-next): A plugin allows you to run any shell commands before or after webpack builds. -- _Maintainer_: `Kuzmin Pavel` [![Github][githubicon]](https://github.com/s00d)
- [Gettext Webpack Plugin](https://github.com/juanluispaz/gettext-webpack-plugin): Embed localization into your bundle using gettext. -- _Maintainer_: `Juan Luis Paz` [![Github][githubicon]](https://github.com/juanluispaz)
- [Node Polyfill Plugin](https://github.com/Richienb/node-polyfill-webpack-plugin): Polyfill Node.js core modules. -- _Maintainer_: `Richie Bendall` [![Github][githubicon]](https://github.com/Richienb) [![Twitter][twittericon]](https://twitter.com/Richienb2)
- [Bytenode Plugin](https://github.com/herberttn/bytenode-webpack-plugin): Compile JavaScript into bytecode using bytenode. -- _Maintainer_: `Herbert Treis Neto` [![Github][githubicon]](https://github.com/herberttn)

### Webpack Tools

- [Webpack Dev Middleware](https://github.com/webpack/webpack-dev-middleware): Middleware which arguments a live bundle. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Webpack Dev Server](https://github.com/webpack/webpack-dev-server): Serves a webpack app. Updates the browser on changes. -- _Maintainer_: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Webpack Merge](https://github.com/survivejs/webpack-merge) - Merge designed for Webpack. -- _Maintainer_: `Juho Vepsäläinen` [![Github][githubicon]](https://github.com/bebraw) [![Twitter][twittericon]](https://twitter.com/bebraw)
- [NPM Install Webpack](https://github.com/ericclemmons/npm-install-webpack-plugin) - Automatically install & save deps with Webpack. -- _Maintainer_: `Eric Clemmons` [![Github][githubicon]](https://github.com/ericclemmons) [![Twitter][twittericon]](https://twitter.com/ericclemmons)
- [Webpack Validator](https://github.com/js-dxtools/webpack-validator) - Validates your webpack config with Joi. -- _Maintainer_: `js-dxtools Team` [![Github][githubicon]](https://github.com/js-dxtools)
- [Webpack Config Utils](https://github.com/kentcdodds/webpack-config-utils) - Util. to make your webpack config easier to read. -- _Maintainer_: `Kent C. Dodds` [![Github][githubicon]](https://github.com/kentcdodds) [![Twitter][twittericon]](https://twitter.com/kentcdodds)
- [Angular2 Webpack Toolkit](https://github.com/AngularClass/webpack-toolkit) - Webpack tools and helpers for Angular 2. -- _Maintainer_: `AngularClass` [![Github][githubicon]](https://github.com/AngularClass) [![Twitter][twittericon]](https://twitter.com/AngularClass)
- [Webpack Bundle Analyzer](https://github.com/th0r/webpack-bundle-analyzer) - Represents bundles as an interactive treemap. -- _Maintainer_: `Yuriy Grunin` [![Github][githubicon]](https://github.com/th0r) [![Twitter][twittericon]](https://twitter.com/grunin_ya)
- [HJS Webpack](https://github.com/HenrikJoreteg/hjs-webpack): Helpers/presets for setting up webpack with hotloading. -- _Maintainer_: `Henrik Joreteg` [![Github][githubicon]](https://github.com/HenrikJoreteg)
- [Webpack Dashboard](https://github.com/FormidableLabs/webpack-dashboard): A CLI dashboard for webpack dev server. -- _Maintainer_: `Formidable Labs` [![Github][githubicon]](https://github.com/FormidableLabs)
- [Neutrino](https://github.com/mozilla-neutrino/neutrino-dev): Combines the power of Webpack with the simplicity of presets. -- _Maintainer_: `Eli Perelman` [![Github][githubicon]](https://github.com/eliperelman)
- [Speed Measure Plugin](https://github.com/stephencookdev/speed-measure-webpack-plugin) - Measures the speed of your webpack plugins and loaders. -- _Maintainer_: `Stephen Cook` [![Github][githubicon]](https://github.com/stephencookdev)
- [packtracker.io](https://packtracker.io/?utm_source=github&utm_medium=awesome-webpack&utm_campaign=social) - Webpack bundle analysis on every commit, report webpack stats to every pull request.
- [BundleStats](https://github.com/bundle-stats/bundle-stats) - Generates bundle report(sizes, assets, modules) and compares the results between different builds. -- _Maintainer_: `Vio` [![Github][githubicon]](https://github.com/vio) [![Twitter][twittericon]](https://twitter.com/vio)
- [Webpack Landing Generator](https://github.com/kuncevic/webpack-landing-generator): Easy way to create landing page that converts. -- _Maintainer_: `Aliaksei Kuncevic` [![Github][githubicon]](https://github.com/kuncevic) [![Twitter][twittericon]](https://twitter.com/kuncevic)
- [Webpack Dev Server Firewall](https://github.com/funbox/webpack-dev-server-firewall): Prevents access to dev server from unknown IPs. -- _Maintainer_: `Igor Adamenko` [![Github][githubicon]](https://github.com/igoradamenko) [![Twitter][twittericon]](https://twitter.com/igoradamenko)

## Research & Training

### Articles

- Aniketh Saha | 16-Oct-19 - [Creating a Custom webpack Plugin](https://alligator.io/js/create-custom-webpack-plugin/)
- Antoine Caron | 18-Jan-19 - [Webpack : an unexpected journey](https://medium.zenika.com/webpack-an-unexpected-journey-26f987efd1c5)
- Mark Erikson | 07-Mar-17 - [Declaratively Rendering Earth in 3D, Building a Cesium + React App with Webpack](http://blog.isquaredsoftware.com/2017/03/declarative-earth-part-1-cesium-webpack/)
- Joseph Zimmerman | 2-Feb-17 - [A Detailed Introduction To Webpack.](https://www.smashingmagazine.com/2017/02/a-detailed-introduction-to-webpack/)
- Jamund Ferguson | 22-Jul-16 - [Manually Tuning Webpack Builds.](https://medium.com/@xjamundx/manually-tuning-webpack-builds-284923f47f44#.lbvkidezh)
- Sean T. Larkin | 21-Jul-16 - [Learn and Debug webpack with Chrome Dev Tools!.](https://medium.com/webpack/webpack-bits-learn-and-debug-webpack-with-chrome-dev-tools-da1c5b19554#.gpoentuxe)
- Raja Rao DV | 10-Apr-16 - [Webpack  —  The Confusing Parts.](https://medium.com/@rajaraodv/webpack-the-confusing-parts-58712f8fcad9#.qmfmplobc)
- Andrew Ray | 09-Apr-16 - [Webpack: When To Use and Why.](http://blog.andrewray.me/webpack-when-to-use-and-why/)
- Jonathan Creamer | 25-Feb-16 - [WebPack Code splitting with ES6 and Babel 6.](http://jonathancreamer.com/webpack-code-splitting-with-es6-and-babel-6/)
- Ilya Zayats | 07-Feb-16 - [How to split your apps by routes with Webpack.](https://medium.com/@somebody32/how-to-split-your-apps-by-routes-with-webpack-36b7a8a6231#.iy99i4f7r)
- Sebastian De Deyne | 04-Feb-16 - [Adventure Time With Webpack.](https://sebastiandedeyne.com/posts/2016/adventure-time-with-webpack)
- Jonathan Creamer | 10-Jan-16 - [Advanced WebPack Part 2 - Code Splitting.](http://jonathancreamer.com/advanced-webpack-part-2-code-splitting)
- Andy Ccs | 02-Jan-16 - [Webpack and Docker for Development and Deployment.](https://medium.com/@andyccs/webpack-and-docker-for-development-and-deployment-ae0e73243db4#.2yutcm8s4)
- Jonathan Creamer | 08-Jun-16 - [Advanced WebPack Part 3 - Creating a custom notifier plugin.](http://jonathancreamer.com/advanced-webpack-part-3-creating-a-custom-notifier-plugin)
- Nader Dabit | 07-Sept-15 - [Beginner’s guide to Webpack.](https://medium.com/@dabit3/beginner-s-guide-to-webpack-b1f1a3638460#.xb01fcsoq)
- Jonathan Creamer | 02-Sept-15 - [Advanced WebPack Part 1 - The CommonsChunk Plugin.](http://jonathancreamer.com/advanced-webpack-part-1-the-commonschunk-plugin/)
- Maxime Fabre | 16-Oct-15 - [Webpack your bags.](https://blog.madewithlove.be/post/webpack-your-bags/?utm_content=buffer480f4&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
- Hridayesh Sharma | 18-Aug-20 - [Webpack Setup for a JavaScript Library](https://www.loginradius.com/engineering/blog/write-a-javascript-library-using-webpack-and-babel/)

### Videos

- Sean Larkin JS Kongress | Apr-2-2019 - [Everything’s a plugin: Understanding webpack from the inside out](https://youtu.be/H3g0BdyVVxA)
- Colt Steele via Youtube| Mar-7-2019 - [Learn Webpack Course](https://www.youtube.com/playlist?list=PLblA84xge2_zwxh3XJqy6UVxS60YdusY8)
- Naomi A. Jacobs via BuzzJS 2.0 2017 | Feb-27-2017 - [Webpack: It's Not Magic](https://www.youtube.com/watch?v=_QEM9kdV-b0)
- Jack Franklin at HalfStack2016 | 18-Nov-16 | [Seamless client side JavaScript w/ Webpack](https://opbeat.com/community/posts/seamless-client-side-javascript-with-webpack-by-jack-franklin)
- Sean Larkin NEJS Conf | 30-Sep-16 | [Webpack: Core Concepts](https://www.youtube.com/watch?v=AZPYL30ozCY&feature=youtu.be)
- Front End Center Webpack from First Principles | 22-Aug-16 - [Intro to Webpack](https://www.youtube.com/watch?v=WQue1AN93YU)
- Eric Clemmons chat with Kent C. Dodds | 01-Jul-16 - [Webpack HMR.](https://www.youtube.com/watch?v=PthDwpgrhmQ)
- Mirko Nasato (5 Part Series) | 07-Jun-16 - [Angular2 with Webpack Project Setup.](https://www.youtube.com/playlist?list=PLgGUMhSgtxJyIQ4vI3BzlCzZLHL79Ew6p)
- Jonathan Creamer at Nodevember | 05-Dec-15 - [Advanced WebPack.](https://www.youtube.com/watch?v=MzVFrIAwwS8)
- Kyle Robinson Young | 08-Jul-15 - [Getting Started with Webpack.](https://www.youtube.com/watch?v=TaWKUpahFZM)
- Tasveer Singh at TorontoJS Tech Talk | 09-Apr-15 - [Webpack.](https://www.youtube.com/watch?v=TaWKUpahFZM)
- Jeremy Lund at Mountain West JS | 28-Mar-15 - [Gift Wrap Your Code with Webpack.](https://www.youtube.com/watch?v=ANMN9M9LhNQ)

### Courses

- [Webpack for Everyone](https://laracasts.com/series/webpack-for-everyone) - Free Laracasts series by [Jeffrey Way](http://twitter.com/jeffrey_way)
- [Webpack Fundamentals](https://frontendmasters.com/courses/webpack-fundamentals/) - Brief introduction about Webpack fundamentals by [Sean Larkin](https://twitter.com/thelarkinn)
- [Web Performance with Webpack](https://frontendmasters.com/courses/performance-webpack/) - Solving common web performance problems using Webpack by [Sean Larkin](https://twitter.com/thelarkinn)
- [Intro to webpack (playlist)](https://egghead.io/playlists/intro-to-webpack-4ca2d994) - Egghead.io playlist of a few videos by [Kent C. Dodds](https://twitter.com/kentcdodds) (the first is free).
- [Angular and Webpack for modular applications](https://egghead.io/courses/angular-and-webpack-for-modular-applications) - Egghead.io course by [Kent C. Dodds](https://twitter.com/kentcdodds)
- [Using Webpack for Production JavaScript Applications](https://egghead.io/courses/using-webpack-for-production-javascript-applications) - Egghead.io course by [Kent C. Dodds](https://twitter.com/kentcdodds) (advanced)
- [Webpack Fundamentals](https://www.pluralsight.com/courses/webpack-fundamentals) - [Joe Eames](https://twitter.com/josepheames) for Pluralsight (intermediate)
- [Webpack Academy](https://webpack.academy) - A comprehensive webpack learning resource.
- [Webpack from scratch series](https://www.youtube.com/playlist?list=PLLhEJK7fQIxB2gZBIzYI50NPsAQERD9rL) on YouTube by Paris Nakita Kejser

### Books

- [SurviveJS - Webpack](http://survivejs.com/webpack/introduction): Free book guiding from a webpack apprentice to master. Covers dev, prod, and advanced topics.

### Webpack Examples

- [Webpack Examples](https://github.com/webpack/webpack/tree/master/examples): Examples of common Webpack functionality.

### Community Examples

#### Angular

- [Angular2 Webpack Starter](https://github.com/AngularClass/angular2-webpack-starter) - A Webpack driven Angular 2 Starter kit from [AngularClass](https://github.com/AngularClass).
- [Angular2 Webpack](https://github.com/preboot/angular2-webpack) - A complete, yet simple, starter for Angular 2 using Webpack from [Preboot](https://github.com/preboot).
- [Angular2 Webpack Visual Studio](https://github.com/damienbod/Angular2WebpackVisualStudio) - ASP.NET Core, Angular2 with Webpack and Visual Studio from [Damien Bod](https://github.com/damienbod).
- [Angular2 Starter](https://github.com/schempy/angular2-typescript-webpack) - Angular2 starter kit with Typescript and Webpack from [Brian Schemp](https://github.com/schempy).
- [Angular2 Seed](https://github.com/angular/angular2-seed/) - A simple starter demonstrating the basic concepts of Angular2 from [Pawel Kozlowski](https://github.com/pkozlowski-opensource).

#### Framework Agnostic

- [ES6 TodoMVC with Webpack](https://github.com/kentcdodds/es6-todomvc) - Repo used to teach webpack. (Check branches). from [Kent C. Dodds](https://github.com/kentcdodds).

#### React

- [Create React App](https://github.com/facebookincubator/create-react-app) - Create React apps with no build configuration from [Dan Abramov](https://github.com/gaearon).
- [React Starter Kit](https://github.com/kriasoft/react-starter-kit) - Isomorphic web app boilerplate from [Kriasoft Team](https://github.com/kriasoft).
- [React Redux Universal](https://github.com/erikras/react-redux-universal-hot-example) - A starter boilerplate for a universal webapp from [Erik Rasmussen](https://github.com/erikras).
- [Frontend Boilerplate](https://github.com/tj/frontend-boilerplate) - A boilerplate of things that mostly shouldn't exist from [TJ Holowaychuk](https://github.com/tj).
- [ReactGo](https://github.com/reactGo/reactGo) - Your One-Stop solution for a full-stack universal Redux from [Ken Ding](https://github.com/choonkending).
- [React Native Calculator](https://github.com/benoitvallon/react-native-nw-react-calculator) - Mobile, desktop and website Apps with the same code from [Benoit Vallon](https://github.com/benoitvallon).
- [React Cordova Boilerplate](https://github.com/unimonkiez/react-cordova-boilerplate) - TodoMVC example for React with Cordova from [Yuval Saraf](https://github.com/unimonkiez).
- [React Universally](https://github.com/ctrlplusb/react-universally) - A starter kit giving you the minimum for a production ready universal react application.
- [Razzle Material-UI Styled Example](https://github.com/kireerik/razzle-material-ui-styled-example) - With Styled Components using Express with compression from [Erik Engi](https://github.com/kireerik).
- [Read](https://github.com/logustra/read) - A highly scalable react boilerplate from [logustra](https://github.com/logustra)

#### Vue

- [Vuad](https://github.com/logustra/vuad) - A highly scalable vue boilerplate from [logustra](https://github.com/logustra)

### Other

- [Juho, Johannes, Tobias & Sean on JavaScript Air](http://jsair.io/webpack) - [JavaScript Air](https://javascriptair.com) podcast
- [Webpack interview questions](https://github.com/styopdev/webpack-interview-questions) - Interview questions with answers.
- [Visual config tool for webpack](https://webpack.jakoblind.no) - A visual tool for creating webpack configs in your browser

[twittericon]: https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg
[githubicon]: https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg