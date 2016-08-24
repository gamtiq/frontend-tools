# Front-end development tools

#### Table of contents <a name="toc"></a>
* [ECMAScript specification](#ecma-specification)
* [JavaScript variant](#js-variant)
* [JavaScript framework](#js-framework)
* [JavaScript UI (view) library / framework](#js-ui-library)
* [JavaScript module system and loader](#loader)
* [Module and asset bundler](#bundler)
* [Package manager](#package-manager)
* [Front-end / CSS framework](#frontend-framework)
* [CSS processor](#css-processor)
* [Testing](#testing)
* [Linting / validation](#linting)
* [Task runner / build tool](#task-runner)
* [Development server](#dev-server)
* [Benchmark](#benchmark)
* [Useful articles & resources](#resources)

### ECMAScript specification <a name="ecma-specification"></a> [&#x2191;](#toc)
* [ECMAScript standard specifications](http://www.ecma-international.org/publications/standards/Ecma-262-arch.htm)
* [Version 3 (PDF)](http://www.ecma-international.org/publications/files/ECMA-ST-ARCH/ECMA-262,%203rd%20edition,%20December%201999.pdf)
* Version 5.1: [HTML](http://www.ecma-international.org/ecma-262/5.1/index.html) | [PDF](http://www.ecma-international.org/publications/files/ECMA-ST-ARCH/ECMA-262%205.1%20edition%20June%202011.pdf)
* Version 6 / 2015: [HTML](http://www.ecma-international.org/ecma-262/6.0/index.html) | [PDF](http://www.ecma-international.org/publications/files/ECMA-ST-ARCH/ECMA-262%206th%20edition%20June%202015.pdf)

### JavaScript variant <a name="js-variant"></a> [&#x2191;](#toc)
* [TypeScript](http://www.typescriptlang.org/)

### JavaScript framework <a name="js-framework"></a> [&#x2191;](#toc)
* [Angular 2](https://angular.io/)
* [Aurelia](http://aurelia.io/)
* [choo](https://github.com/yoshuawuyts/choo) - framework for creating sturdy frontend applications.
* [Ember](http://emberjs.com/)

### JavaScript UI (view) library / framework <a name="js-ui-library"></a> [&#x2191;](#toc)
* [Inferno](http://infernojs.org/) - An extremely fast, React-like JavaScript library for building modern user interfaces.
* [Marko Widgets](http://markojs.com/) - a UI component building library that utilizes Marko templates as the view. It offers advanced features like DOM diffing/patching, batched updates, stateful widgets, declarative event binding and efficient event delegation.
* [Monkberry](http://monkberry.js.org/) - blazingly fast, small and simple JavaScript library for building web user interfaces.
* [Preact](https://preactjs.com/) - Fast 3kb alternative to React with the same ES6 API.
* [React](https://facebook.github.io/react/) - A JavaScript library for building user interfaces.
* [Riot](http://riotjs.com/) - A React-like user interface micro-library.
* [Vue.js](http://vuejs.org/) - Simple yet powerful library for building modern web interfaces.

### JavaScript module system and loader <a name="loader"></a> [&#x2191;](#toc)
* AMD:
  - [curl.js](https://github.com/cujojs/curl) (outdated)
  - [require.js](http://requirejs.org/)
  - [SystemJS](https://github.com/systemjs/systemjs)
* CommonJS:
  - [Cajon](https://github.com/requirejs/cajon)
  - [Inject](http://www.injectjs.com/)
  - [require1k](https://github.com/Stuk/require1k)
  - [SystemJS](https://github.com/systemjs/systemjs)
* ECMAScript 6:
  - [SystemJS](https://github.com/systemjs/systemjs)

### Module and asset bundler <a name="bundler"></a> [&#x2191;](#toc)
* [Browserify](http://browserify.org/)
* [gluejs](http://mixu.net/gluejs/)
* [Rollup](http://rollupjs.org/)
* [SystemJS Builder](https://github.com/systemjs/builder) 
* [webpack](http://webpack.github.io/)

### Package manager <a name="package-manager"></a> [&#x2191;](#toc)
* [Bower](https://bower.io/)
* [Duo](http://duojs.org/)
* [jspm](http://jspm.io/)
* [npm](https://www.npmjs.com/)

### Front-end / CSS framework <a name="frontend-framework"></a> [&#x2191;](#toc)
* [Blaze](http://blazecss.com/)
* [Bootflat](http://bootflat.github.io/) (Bootstrap-based)
* [Bootstrap](http://getbootstrap.com/)
* [Bulma](http://bulma.io/) - A modern CSS framework based on Flexbox.
* [Cutestrap](https://www.cutestrap.com/)
* [Flat UI](http://designmodo.github.io/Flat-UI/) - a beautiful theme for Bootstrap.
* [Foundation](http://foundation.zurb.com/)
* [GroundworkCSS](http://groundworkcss.github.io/)
* [Ink](http://ink.sapo.pt/)
* [inuitcss](https://github.com/inuitcss/getting-started)
* [Kube](https://imperavi.com/kube/) - a web framework for professional developers and designers alike. Kube is a wireframe, a skeleton for your project, in a way.
* [Leaf](http://getleaf.com/) - A CSS framework based on Google's material design.
* [Materialize](http://materializecss.com/)
* [Material Framework](http://nt1m.github.io/material-framework/)
* [Material-UI](http://www.material-ui.com) (React components)
* [Metro UI](http://metroui.org.ua/) - The front-end framework for developing projects on the web in Windows Metro Style.
* [Polymer](http://www.polymer-project.org/)
* [Pure](http://purecss.io/) - A set of small, responsive CSS modules that you can use in every web project.
* [Semantic UI](http://semantic-ui.com/) - a development framework that helps create beautiful, responsive layouts using human-friendly HTML.
* [Skeleton](http://getskeleton.com/) - A dead simple, responsive boilerplate.
* [Topcoat](http://topcoat.io/)
* [Turret](http://turretcss.com/) - a styles and browser behaviour normalisation framework for rapid development of responsive and accessible websites.
* [UIkit](http://getuikit.com/) - A lightweight and modular front-end framework for developing fast and powerful web interfaces.
* [Zimit](http://firezenk.github.io/zimit/) - Awesome, solid, responsive and complete front-end prototyping framework for web-developers.

### CSS processor <a name="css-processor"></a> [&#x2191;](#toc)
* [EQCSS](http://elementqueries.com/) - A CSS Extension for Element Queries & More.
* [Less](http://lesscss.org/)
* [PostCSS](http://postcss.org/) - A tool for transforming CSS with JavaScript.
* [Sass](http://sass-lang.com/)
* [Stylus](http://stylus-lang.com/)

### Testing <a name="testing"></a> [&#x2191;](#toc)
* [AVA](https://github.com/avajs/ava)
* [Intern](http://theintern.github.io/)
* [Jasmine](http://jasmine.github.io/)
* [Jest](http://facebook.github.io/jest/)
* [Karma](http://karma-runner.github.io/)
* [Mocha](http://mochajs.org/)
* [QUnit](http://qunitjs.com/)
* [tape](https://github.com/substack/tape)
* [Testem](https://github.com/testem/testem)

### Linting / validation <a name="linting"></a> [&#x2191;](#toc)
* CSS
  - [CSSLint](https://github.com/CSSLint/csslint)
  - [stylelint](http://stylelint.io/)
* HTML
  - [HTML Inspector](https://github.com/philipwalton/html-inspector)
  - [HTMLHint](http://htmlhint.com/)
* JavaScript
  - [JSHint](www.jshint.com)
  - [ESLint](http://eslint.org/)

### Task runner / build tool <a name="task-runner"></a> [&#x2191;](#toc)
* [Brunch](http://brunch.io/)
* [Grunt](http://gruntjs.com/)
* [Gulp](http://gulpjs.com/)

### Development server <a name="dev-server"></a> [&#x2191;](#toc)
* [EasyMock Server](https://github.com/cyberagent/node-easymock)
* [freddie](https://github.com/Scytl/freddie)
* [http-server](https://github.com/indexzero/http-server) - a simple, zero-configuration command-line http server.
* [Puer](https://github.com/leeluolee/puer) - more than a live-reload server , built for efficient frontend development.
* [servedir](https://github.com/evanw/servedir) - a simple Node web server for offline development and testing: running servedir from a directory will create a quick local web server.
* [server-with-benefits](https://github.com/galbi101/server-with-benefits) - A static Node.js file web server with options for proxing requests and delaying/mocking responses.
* [Superstatic (with proxy)](https://github.com/colinbate/superstatic-with-proxy)

### Benchmark <a name="benchmark"></a> [&#x2191;](#toc)
* [JS web frameworks benchmark – Round 3](http://www.stefankrause.net/wp/?p=301)
* [UI Benchmark](https://localvoid.github.io/uibench/)

### Useful articles & resources <a name="resources"></a> [&#x2191;](#toc)
* [The cost of transpiling es2015 in 2016](https://github.com/samccone/The-cost-of-transpiling-es2015-in-2016)
* [What Do the Popular JavaScript Tools Depend On?](http://developer.telerik.com/featured/popular-javascript-tools-depend/)

[Table of contents &#x2191;](#toc)
