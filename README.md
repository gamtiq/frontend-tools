# Front-end development tools (mostly)

#### Table of contents <a name="toc"></a>
* [Tools catalog / search / discovery / comparison service](#tool-search)
* [ECMAScript / JavaScript](#ecmascript)
    - [Specification](#es-specification)
    - [Support / compatibility](#es-support)
    - [Documentation, guide](#es-doc)
* [JavaScript variant / compiler / transpiler](#js-variant)
* [JavaScript framework](#js-framework)
* [JavaScript UI (view) library / framework](#js-ui-library)
* [React-based library / framework / platform](#react-library)
* [Vue-based library / framework](#vue-library)
* [Front-end / CSS framework](#frontend-framework)
    - [Small CSS library / toolkit](#small-css-library)
* [Shim, polyfill](#shim)
* [Web development](#web-dev)
* [Mobile development](#mobile-dev)
* [Desktop development](#desktop-dev)
* [Data / model / state management library](#state-management)
* [Database](#database)
* [Internationalization (i18n), localization (l10n)](#i18n)
* [JavaScript utility library](#js-utility-library)
* [JavaScript module system and loader](#loader)
* [Module and asset bundler](#bundler)
* [Package manager](#package-manager)
* [CSS processor](#css-processor)
* [Linting, validation, checklist](#linting)
* [Testing](#testing)
* [Debug](#debug)
* [Documentation](#documentation)
* [Code processing](#code-processing)
* [Minification](#mini)
* [Task runner, build tool](#task-runner)
* [Automation](#automation)
* [Boilerplate, scaffolding](#boilerplate)
* [Component development](#component-dev)
* [Design](#design)
* [Images, icons](#images)
* [Analysis, performance, optimization](#analysis)
* [Version control](#version-control)
    - [Git](#git)
* [Development server](#dev-server)
    - [Node.js-based](#dev-server-node)
    - [With PHP support](#dev-server-php)
* [Node.js version management](#node-manage)
* [Editor, IDE](#editor)
* [API](#api)
* [Playground, online development](#playground)
* [Site generator](#site-generator)
* [Emulator, simulator](#emulator)
* [Browser extension](#browser-extension)
* [Benchmark](#benchmark)
* [Hosting, cloud services](#hosting)
* [Guide, reference, practices, recipes](#guide)
* [Books](#books)
* [Examples](#examples)
* [Useful articles & resources](#resources)

### Tools catalog / search / discovery / comparison service <a name="tool-search"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [AlternativeTo](https://alternativeto.net/) - A free service that helps you find better alternatives to the products you love and hate.
* [awesome](https://awesome.re/) - A curated list of awesome lists.
* [awesome-react-components](http://devarchy.com/react-components) - Catalog of React components / libraries.
* [Best of JavaScript](https://bestofjs.org/) - A place to find the best components to build amazing web applications.
* [CSS Script](http://www.cssscript.com/) - A Javascript & CSS code library aims to provide the newest, best and free CSS & javascript resources for web/mobile developers and designers.
* [headlesscms.org](https://headlesscms.org/) - A list of content management systems for JAMstack sites.
* [iReact](http://ireact.cn/) - Helps you discover the most fantastic, powerful React Components and Libraries, and makes it easy for you to pick one that’ll work for you.
* [JavaScripting](http://www.javascripting.com/) - The definitive source of the best JavaScript libraries, frameworks, and plugins.
* [JavaScriptOO](http://www.javascriptoo.com/) - Every javascript project you should be looking into with examples, categories, install commands, CDN links, project and author stats, and more.
* [jQuery Plugins](http://jquery-plugins.net/) - Categorized collection of jQuery plugins.
* [JqueryScript.Net](http://www.jqueryscript.net/) - One of jQuery Plugin websites that provide web designers and developers with a simple way to preview and download a variety of Free jQuery Plugins.
* [JSter](http://jster.net/) - A catalog of frontend JavaScript libraries.
* [JS.coach](https://js.coach/) - An opinionated catalog of open source JS packages.
* [LibHunt](https://www.libhunt.com/) -  Our goal is to help you find the software and libraries you need. All lists have been crafted by many experts from the relevant GitHub communities.
* [Libraries.io](https://libraries.io/) - Helps developers find new open source libraries, modules and frameworks and keep track of ones they depend upon.
* [MicroJS](http://microjs.com) - Fantastic Micro-Frameworks and Micro-Libraries for Fun and Profit!
* [Node Frameworks](http://nodeframework.com/) - Hand-picked registry of Node.js frameworks.
* [NPMCompare](https://npmcompare.com/) - Search and compare npm packages.
* [npms](https://npms.io/) - A better and open source search for node modules.
* [npmsearch](http://npmsearch.com/) - Search for node packages on the npm registry.
* [npm trends](http://www.npmtrends.com/) - Compare package download counts over time.
* [Pika](https://www.pikapkg.com/) - Search modern ESM packages on npm.
* [Redux Ecosystem Links](https://github.com/markerikson/redux-ecosystem-links) - A categorized list of addon libraries for Redux, as well as other libraries that are closely related.
* [StackShare](https://stackshare.io/) - Discover & discuss the best software tools & services.
* [StaticGen.com](https://www.staticgen.com/) - A leaderboard of top open-source static site generators.
* [Unheap](http://www.unheap.com/) - A tidy repository of JavaScript plugins.
* [VueScript.com](http://www.vuescript.com/) - Aims to offer latest free Vue.js components for web application developers.
* [webcomponents.org](https://www.webcomponents.org/) - A place to publish, browse and search for reusable web UI components.

### ECMAScript / JavaScript <a name="ecmascript"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* Specification <a name="es-specification"></a>
    - [ECMAScript standard specifications](http://www.ecma-international.org/publications/standards/Ecma-262-arch.htm)
    - [Version 3 (PDF)](http://www.ecma-international.org/publications/files/ECMA-ST-ARCH/ECMA-262,%203rd%20edition,%20December%201999.pdf)
    - Version 5.1: [HTML](http://www.ecma-international.org/ecma-262/5.1/index.html) | [PDF](http://www.ecma-international.org/publications/files/ECMA-ST-ARCH/ECMA-262%205.1%20edition%20June%202011.pdf)
    - Version 6 / 2015: [HTML](http://www.ecma-international.org/ecma-262/6.0/index.html) | [PDF](http://www.ecma-international.org/publications/files/ECMA-ST-ARCH/ECMA-262%206th%20edition%20June%202015.pdf)
    - Version 8 / 2017: [HTML](https://www.ecma-international.org/ecma-262/8.0/index.html) | [PDF](https://www.ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf)
    - [TC39 Proposals](https://prop-tc39.now.sh/)
* Support / compatibility <a name="es-support"></a>
    - [ECMAScript compatibility tables](https://kangax.github.io/compat-table/)
    - [node.green](http://node.green/) - Node.js ECMAScript compatibility tables.
* Documentation, guide <a name="es-doc"></a>
    - [es6features](https://github.com/lukehoban/es6features) - Overview of ECMAScript 6 features.
    - [Exploring JS](http://exploringjs.com/) - JavaScript books for programmers.

### JavaScript variant / compiler / transpiler <a name="js-variant"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Babel](http://babeljs.io/) - a JavaScript compiler.
* [Bublé](https://buble.surge.sh/) - fast, batteries-included ES2015 compiler.
* [TypeScript](http://www.typescriptlang.org/) - a typed superset of JavaScript that compiles to plain JavaScript.

### JavaScript framework <a name="js-framework"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Angular 2](https://angular.io/) - a development platform for building mobile and desktop web applications.
* [Aurelia](http://aurelia.io/) - a JavaScript client framework for mobile, desktop and web leveraging simple conventions and empowering creativity.
* [choo](https://github.com/yoshuawuyts/choo) - framework for creating sturdy frontend applications.
* [cyclow](http://cyclow.js.org) - a reactive frontend framework.
* [Ember](http://emberjs.com/) - a framework for creating ambitious web applications.
* [HyperApp](https://github.com/hyperapp/hyperapp) - a JavaScript library for building frontend applications.
* [Mithril](https://mithril.js.org/) - a modern client-side Javascript framework for building Single Page Applications.
* [qooxdoo](http://www.qooxdoo.org/) - a universal JavaScript framework that enables you to create applications for a wide range of platforms.

### JavaScript UI (view) library / framework <a name="js-ui-library"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Cell](https://www.celljs.org/) - A self-constructing web app framework powered by a self-driving DOM.
* [Inferno](http://infernojs.org/) - An extremely fast, React-like JavaScript library for building modern user interfaces.
* [jComponent](https://jcomponent.org/) - A component library for creating reusable components with jQuery.
* [Marko](http://markojs.com/) - A friendly (and fast!) UI library that makes building web apps fun.
* [Melody](https://melody.js.org/) - A fast and memory efficient library for creating highly dynamic user interfaces.
* [Monkberry](http://monkberry.js.org/) - Blazingly fast, small and simple JavaScript library for building web user interfaces.
* [Moon](https://kbrsh.github.io/moon) - A minimal & fast UI library.
* [Nerv](https://nerv.aotu.io/) - A blazing fast React alternative, compatible with IE8 and React 16.
* [Preact](https://preactjs.com/) - Fast 3kb alternative to React with the same ES6 API.
* [Ractive.js](https://ractive.js.org/) - A JavaScript library for building reactive user interfaces in a way that doesn't force you into a particular framework's way of thinking.
* [React](https://facebook.github.io/react/) - A JavaScript library for building user interfaces.
* [Riot](https://riot.js.org/) - Simple and elegant component-based UI library.
* [Svelte](https://svelte.technology/) - Rather than interpreting your application code at run time, your app is converted into ideal JavaScript at build time.
* [Vue.js](http://vuejs.org/) - Simple yet powerful library for building modern web interfaces.

### React-based library / framework / platform <a name="react-library"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Ant Design](https://ant.design/docs/react/introduce) - An enterprise-class UI design language and React-based implementation.
* [Blueprint](http://blueprintjs.com/) - A React-based UI toolkit for the web. It is optimized for building complex, data-dense web interfaces for desktop applications.
* [dva](https://github.com/dvajs/dva) - React and Redux based, lightweight and Elm-style framework.
* [Electrode](http://www.electrode.io/) - A platform for building universal React/Node.js applications with standardized structure, best practices, and modern technologies baked in.
* [Elemental UI](http://elemental-ui.com/) - A UI Toolkit for React.js Websites and Apps.
* [Essence](http://getessence.io) - The Essential Material Design Framework.
* [Grommet](http://grommet.github.io/) - The most advanced UX framework for enterprise applications.
* [libreact](https://github.com/streamich/libreact) - a collection of most essential React utilities you will probably need in any project.
* [Material-UI](http://www.material-ui.com/) - A Set of React Components that Implement Google's Material Design.
* [react-md](http://react-md.mlaursen.com/) - A set of React components and sass files for implementing Google's Material Design.
* [React-MDL](https://react-mdl.github.io/react-mdl/) - A set of React components build on top of Material Design Lite.
* [React Toolbox](http://react-toolbox.com) - A set of React components that implement Google's Material Design specification.
* [ReactXP](https://microsoft.github.io/reactxp/) - A library for cross-platform app development using React and React Native.
* [Rebass](http://jxnblk.com/rebass/) - Configurable React Stateless Functional UI Components.

### Vue-based library / framework <a name="vue-library"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [BalmUI](https://material.balmjs.com/) - next generation Material UI for Vue.js.
* [Buefy](https://buefy.org/) - a lightweight library of responsive UI components for Vue.js based on Bulma framework and design.
* [Element](http://element.eleme.io/) - a Vue.js 2.0 UI Toolkit for Web.
* [iView](https://www.iviewui.com/) - a high quality UI Toolkit built on Vue.js.
* [Keen UI](https://josephuspaye.github.io/Keen-UI/) - a lightweight collection of essential UI components written with Vue.js and inspired by Material Design.
* [Muse UI](https://museui.github.io/) - a Vue 2.0 and Material Design based UI component library.
* [Quasar Framework](https://quasar.dev/) - build high-performance VueJS user interfaces in record time.
* [Vuetify.js](https://vuetifyjs.com/) - a component framework for Vue.js 2.
* [Vue Material](https://vuematerial.github.io/) - lightweight framework built exactly according to the Material Design specs. It aims to deliver a collection of reusable components and a series of UI Elements to build applications with support to all modern Web Browsers through Vue 2.

### Front-end / CSS framework <a name="frontend-framework"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Blaze](https://www.blazeui.com/) - an open source modular toolkit. It provides great structure for building websites quickly with a scalable and maintainable foundation.
* [Bootflat](http://bootflat.github.io/) - an open source Flat UI KIT based on Bootstrap 3.3.0 CSS framework.
* [Bootstrap](https://getbootstrap.com/) - an open source toolkit for developing with HTML, CSS, and JS.
* [Bulma](https://bulma.io/) - a modern CSS framework based on Flexbox.
* [Flat UI](http://designmodo.github.io/Flat-UI/) - a beautiful theme for Bootstrap.
* [Foundation](https://foundation.zurb.com/) - the most advanced responsive front-end framework in the world.
* [Froala Design Blocks](https://www.froala.com/design-blocks) - a set of 170+ Bootstrap based design blocks ready to be used to create clean modern websites.
* [GroundworkCSS](http://groundworkcss.github.io/) (outdated) - a fully responsive HTML5, CSS and Javascript toolkit.
* [Ink](http://ink.sapo.pt/) - an interface kit for quick development of web interfaces, simple to use and expand on.
* [inuitcss](https://github.com/inuitcss/inuitcss) - extensible, scalable, Sass-based, OOCSS framework for large and long-lasting UI projects. It does not provide you with UI and design out of the box, instead, it provides you with a solid architectural baseline upon which to complete your own work.
* [Kube](https://imperavi.com/kube/) - clean, minimalistic and fast to implement CSS & JS framework for professional developers and designers alike.
* [Leaf](http://getleaf.com/) (outdated) - a CSS framework based on Google's material design.
* [Material Components for the web](https://github.com/material-components/material-components-web) - modular and customizable Material Design UI components for the web. Developed by a core team of engineers and UX designers at Google, these components enable a reliable development workflow to build beautiful and functional web projects.
* [Material Design Lite](https://getmdl.io/) - lets you add a Material Design look and feel to your websites. It doesn’t rely on any JavaScript frameworks and aims to optimize for cross-device use, gracefully degrade in older browsers, and offer an experience that is immediately accessible.
* [Material Framework](http://nt1m.github.io/material-framework/) - a simple responsive CSS framework that allows you to integrate Material Design in any web page or web app.
* [Materialize](https://materializecss.com/) - a modern responsive front-end framework based on Material Design.
* [Metro UI](https://metroui.org.ua/) - sleek, intuitive, and powerful front-end framework for faster and easier web development. Build responsive, mobile-first projects on the web with the first front-end component library in Metro Style.
* [Polymer](https://www.polymer-project.org/) - libraries, tools and patterns to help developers build modern Progressive Web Apps, taking full advantage of cutting-edge platform features like Web Components, Service Workers and HTTP/2.
* [Semantic UI](https://semantic-ui.com/) - a development framework that helps create beautiful, responsive layouts using human-friendly HTML.
* [Spectre.css](https://picturepan2.github.io/spectre/) - a lightweight, responsive and modern CSS framework.
* [Tailwind CSS](https://tailwindcss.com/) - a utility-first CSS framework for rapid UI development.
* [Topcoat](http://topcoat.io/) - CSS for clean and fast web apps.
* [Turret](https://turretcss.com/) - a styles and browser behaviour normalisation framework for rapid development of responsive and accessible websites.
* [UIkit](https://getuikit.com/) - a lightweight and modular front-end framework for developing fast and powerful web interfaces.
* Small CSS library / toolkit <a name="small-css-library"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
    - [Basscss](http://basscss.com/) - low-Level CSS Toolkit, a lightweight collection of immutable utilities designed for speed, clarity, performance, and scalability.
    - [Cutestrap](https://www.cutestrap.com/) - a sassy, opinionated CSS Framework. A tiny alternative to Bootstrap.
    - [mini.css](https://minicss.org/) - a minimal, responsive, style-agnostic CSS framework.
    - [Mobi.css](http://getmobicss.com/) - a lightweight, scalable, mobile-first css framework.
    - [Picnic CSS](https://picnicss.com/) - an invasive CSS library to get your style started.
    - [Pure](https://purecss.io/) - a set of small, responsive CSS modules that you can use in every web project.
    - [Skeleton](http://getskeleton.com/) - a dead simple, responsive boilerplate.
    - [Tachyons](http://tachyons.io/) - create fast loading, highly readable, and 100% responsive interfaces with as little css as possible.
    - [Wing](https://kbrsh.github.io/wing/) - a beautiful CSS framework designed for minimalists.

### Shim, polyfill <a name="shim"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [core-js](https://github.com/zloirock/core-js) - modular standard library for JavaScript. Includes polyfills for ECMAScript 5, 2015, 2016, 2017.
* [ECMAScript Shims](https://github.com/es-shims) - a community host for shims and polyfills that are compliant to EcmaScript specs.
    - [es5-shim](https://github.com/es-shims/es5-shim) - monkey-patch a JavaScript context to contain all EcmaScript 5 methods that can be faithfully emulated with a legacy JavaScript engine.
    - [es6-shim](https://github.com/es-shims/es6-shim) - provides compatibility shims so that legacy JavaScript engines behave as closely as possible to ECMAScript 6.
    - [es7-shim](https://github.com/es-shims/es7-shim) - contains shims that can be used to monkeypatch a JavaScript context to contain all ECMAScript 7 methods that can be faithfully emulated with a legacy JavaScript engine.
* [Intl.js](https://github.com/andyearnshaw/Intl.js/) - compatibility implementation of the ECMAScript Internationalization API (ECMA-402) for JavaScript.

### Web development <a name="web-dev"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Next.js](https://nextjs.org/) - a JavaScript framework that lets you build server-side rendering and static web applications using React.
* [Zero](https://zeroserver.io/) - a web framework to simplify modern web development. It's as simple as writing your code in a mix of Node.js, React, HTML, MDX, Vue, and static files and putting them all in a folder. Zero abstracts the usual project configuration for routing, bundling, and transpiling to make it easier to get started.

### Mobile development <a name="mobile-dev"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Ionic](https://ionicframework.com/framework) - the open-source mobile app development framework that makes it easy to build top quality native and progressive web apps with web technologies.
* [NativeScript](https://www.nativescript.org/) - an open source framework for building truly native mobile apps with JavaScript and CSS.
* [React Native](https://facebook.github.io/react-native/) - build native mobile apps using JavaScript and React.

### Desktop development <a name="desktop-dev"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Electron](https://electronjs.org/) - a framework that lets you write cross-platform desktop applications using JavaScript, HTML and CSS.
* [NW.js](https://nwjs.io/) - an app runtime based on Chromium and node.js. You can write native apps in HTML and JavaScript with NW.js.
* [Proton Native](https://proton-native.js.org/) - a React environment for cross platform native desktop apps.

### Data / model / state management library <a name="state-management"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Breeze](http://www.getbreezenow.com/breezejs) - the data management library for developers of rich client applications written in JavaScript. If you store data in a database, query and save those data as complex object graphs, and share these graphs across multiple screens of your JavaScript client, Breeze is for you.
* [Cerebral](http://www.cerebraljs.com/) - a state controller with its own debugger.
* [freactal](https://github.com/FormidableLabs/freactal) - a composable state management library for React.
* [JSData](http://www.js-data.io/) - inspired by Ember Data, JSData is the model layer you've been craving. It consists of a convenient framework-agnostic, in-memory store for managing your data, which uses adapters to communicate with various persistence layers.
* [Microstates](https://github.com/microstates/microstates.js) - a functional runtime type system designed to ease state management in component based applications. It allows you to declaratively compose application state from atomic state machines.
* [MobX](https://mobxjs.github.io/mobx/) - a battle tested library that makes state management simple and scalable by transparently applying functional reactive programming.
* [NuclearJS](https://optimizely.github.io/nuclear-js/) - reactive Flux built with ImmutableJS data structures.
* [Overmind](https://overmindjs.org) - frictionless state management. Overmind aims for a developer experience where that is all you focus on, reducing the orchestration of state management to a minimum.
* [Redux](http://redux.js.org/) - a predictable state container for JavaScript apps.
* [Rematch](https://rematch.gitbooks.io/rematch) - Redux best practices without the boilerplate.
* [Storeon](https://github.com/storeon/storeon) - a tiny event-based Redux-like state manager for React and Preact.
* [Transis](https://github.com/centro/transis) - a JavaScript data modeling library useful for creating rich client-side experiences.
* [WatermelonDB](https://github.com/Nozbe/WatermelonDB) - build powerful React and React Native apps that scale from hundreds to tens of thousands of records and remain fast.

### Database <a name="database"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [AlaSQL](http://alasql.org/) - JavaScript SQL database for browser and Node.js. Handles both traditional relational tables and nested JSON data (NoSQL). Export, store, and import data from localStorage, IndexedDB, or Excel.
* [DataScript](https://github.com/tonsky/datascript) - immutable database and Datalog query engine for Clojure, ClojureScript and JS.
* [ForerunnerDB](http://www.forerunnerdb.com) - a NoSQL JavaScript JSON database with a query language based on MongoDB (with some differences) and runs on browsers and Node.js.
* [LokiJS](http://lokijs.org) - a fast, in-memory document-oriented datastore for node.js, browser and cordova.
* [Lowdb](https://github.com/typicode/lowdb) - a small local database for small projects (powered by lodash API).
* [NeDB](https://github.com/louischatriot/nedb) - embedded persistent or in memory database for Node.js, nw.js, Electron and browsers, 100% JavaScript, no binary dependency.
* [PouchDB](https://pouchdb.com/) - an open-source JavaScript database inspired by Apache CouchDB that is designed to run well within the browser. It enables applications to store data locally while offline, then synchronize it with CouchDB and compatible servers when the application is back online, keeping the user's data in sync no matter where they next login.
* [RxDB](https://github.com/pubkey/rxdb) - reactive, serverless, client-side, offline-first database.
* [TingoDB](http://www.tingodb.com/) - an embedded JavaScript in-process filesystem or in-memory database upwards compatible with MongoDB at the API level.

### Internationalization (i18n), localization (l10n) <a name="i18n"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [FormatJS](https://formatjs.io/) - a modular collection of JavaScript libraries for internationalization that are focused on formatting numbers, dates, and strings for displaying to people. It includes a set of core libraries that build on the JavaScript Intl built-ins and industry-wide i18n standards, plus a set of integrations for common template and component libraries.
* [Globalize](https://globalizejs.com/) - a JavaScript library for internationalization and localization that leverage the official Unicode CLDR JSON data. Globalize provides number formatting and parsing, date and time formatting and parsing, currency formatting, message formatting (ICU message format pattern), and plural support.
* [i18next](https://www.i18next.com/) - an internationalization-framework written in and for JavaScript. It provides you with a complete solution to localize your product from web to mobile and desktop.

### JavaScript utility library <a name="js-utility-library"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [101](https://github.com/tjmehta/101) - a modern JS utility library.
* [Lodash](https://lodash.com/) - a modern JavaScript utility library delivering modularity, performance & extras.
* [Mout](http://moutjs.com/) - a collection of modular JavaScript utilities that can be used in the browser as AMD modules or on node.js.
* [Sugar](https://sugarjs.com/) - a Javascript utility library for working with native objects.
* [Underscore](http://underscorejs.org/) - a JavaScript library that provides a whole mess of useful functional programming helpers without extending any built-in objects.

### JavaScript module system and loader <a name="loader"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [SystemJS](https://github.com/systemjs/systemjs) - dynamic ES module loader.
* AMD:
    - [curl.js](https://github.com/cujojs/curl) (outdated) - a small and very fast AMD-compliant asynchronous loader.
    - [require.js](https://requirejs.org/) - a JavaScript file and module loader.
* CommonJS:
    - [Cajon](https://github.com/requirejs/cajon) - a JavaScript module loader for the browser that can load CommonJS/node and AMD modules. It is built on top of RequireJS.
    - [Inject](http://www.injectjs.com/) (outdated) - AMD and CJS dependency management in the browser.
    - [require1k](https://github.com/Stuk/require1k) - a minimal, and yet practically useful, CommonJS/Node.js require module loader for the browser in under 1000 bytes.
* ECMAScript 6:
    - [@pika/web](https://github.com/pikapkg/web) - run npm dependencies directly in the browser. No Browserify, Webpack or import maps required.

### Module and asset bundler <a name="bundler"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Browserify](http://browserify.org/) - lets you `require('modules')` in the browser by bundling up all of your dependencies.
* [FuseBox](http://fuse-box.org/) - a bundler/module loader that combines the power of webpack, JSPM and SystemJS. It will compile and bundle your code within a fraction of a second, yet offering a comprehensive loader API.
* [gluejs](http://mixu.net/gluejs/) - package Node/CommonJS modules for the browser.
* [Lasso.js](https://github.com/lasso-js/lasso) - JavaScript module bundler that also provides first-level support for optimally delivering JavaScript, CSS, images and other assets to the browser. Offers many different optimizations such as a bundling, code splitting, lazy loading, conditional dependencies, compression and fingerprinted resource URLs.
* [Microbundle](https://github.com/developit/microbundle) - zero-configuration bundler for tiny modules.
* [Parcel](https://parceljs.org/) - blazing fast, zero configuration web application bundler.
* [@pika/pack](https://github.com/pikapkg/pack) - developer tool that uses simple, pre-configured build plugins to create your modern package.
* [Poi](https://poi.js.org/) - develop powerful web app with no build configs until you need.
* [Rollup](http://rollupjs.org/) - a module bundler for JavaScript which compiles small pieces of code into something larger and more complex, such as a library or application.
* [SystemJS Builder](https://github.com/systemjs/builder) - provides a single-file build for SystemJS of mixed-dependency module trees.
* [webpack](https://webpack.js.org/) - a module bundler. Its main purpose is to bundle JavaScript files for usage in a browser, yet it is also capable of transforming, bundling, or packaging just about any resource or asset.

### Package manager <a name="package-manager"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Bower](https://bower.io/) (outdated) - a package manager for the web.
* [Duo](http://duojs.org/) (outdated, [Github repository](https://github.com/duojs/duo)) - a next-generation package manager that blends the best ideas from Component, Browserify and Go to make organizing and writing front-end code quick and painless.
* [jspm](https://jspm.io/) - registry and format agnostic JavaScript package manager for the SystemJS universal module loader.
* [npm](https://www.npmjs.com/) - a package manager for JavaScript.
* [pnpm](https://pnpm.js.org/) - fast, disk space efficient package manager.

### CSS processor <a name="css-processor"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [EQCSS](http://elementqueries.com/) - A CSS Extension for Element Queries & More.
* [Less](http://lesscss.org/) - The dynamic stylesheet language.
* [PostCSS](http://postcss.org/) - A tool for transforming CSS with JavaScript.
* [Sass](http://sass-lang.com/) - An extension of CSS, adding nested rules, variables, mixins, selector inheritance, and more. 
* [Stylus](http://stylus-lang.com/) - Expressive, robust, feature-rich language, providing an efficient, dynamic, and expressive way to generate CSS. 

### Linting, validation, checklist <a name="linting"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Front-End Checklist](https://frontendchecklist.io/) - an exhaustive list of all elements you need to have / to test before launching your site / HTML page to production.
* [webhint](https://webhint.io/) - a linting tool for the web.
* [Web Developer Checklist](http://webdevchecklist.com/) - the ultimate checklist for all serious web developers building modern websites.
* CSS
    - [CSSLint](https://github.com/CSSLint/csslint) - a tool to help point out problems with your CSS code. It does basic syntax checking as well as applying a set of rules to the code that look for problematic patterns or signs of inefficiency. The rules are all pluggable, so you can easily write your own or omit ones you don't want.
    - [stylelint](https://stylelint.io/) - a mighty, modern linter that helps you avoid errors and enforce conventions in your styles.
* HTML
    - [HTML Inspector](https://github.com/philipwalton/html-inspector) - a highly-customizable, code quality tool to help you write better markup.
    - [HTMLHint](https://github.com/htmlhint/HTMLHint) - the static code analysis tool you need for your HTML.
* JavaScript and variants
    - [ESLint](https://eslint.org/) - the pluggable linting utility for JavaScript and JSX.
    - [JSHint](https://jshint.com/) - a tool that helps to detect errors and potential problems in your JavaScript code.
    - [TSLint](https://palantir.github.io/tslint/) - an extensible static analysis tool that checks TypeScript code for readability, maintainability, and functionality errors. It is widely supported across modern editors & build systems and can be customized with your own lint rules, configurations, and formatters.
    - [XO](https://github.com/xojs/xo) - opinionated but configurable ESLint wrapper with lots of goodies included.

### Testing <a name="testing"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [AVA](https://github.com/avajs/ava)
* [BackstopJS](https://garris.github.io/BackstopJS/) - automates visual regression testing of your responsive web UI by comparing DOM screenshots over time.
* [CodeceptJS](http://codecept.io/) - acceptance testing framework for NodeJS. CodeceptJS is a testing framework for end-to-end testing with WebDriver (or others). It abstracts browser interaction to simple steps which is written from a user perspective.
* [Cypress](https://www.cypress.io/) - a test engine that runs unit and integration tests in your browser.
* [Enzyme](https://github.com/airbnb/enzyme) - a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components' output.
* [Intern](http://theintern.github.io/)
* [Jasmine](http://jasmine.github.io/)
* [Jest](https://jestjs.io/)
* [Karma](http://karma-runner.github.io/)
* [Mocha](http://mochajs.org/)
* [QUnit](http://qunitjs.com/)
* [Sazerac](http://sazeracjs.com/) - data-driven testing for JavaScript. It helps you create simple, readable tests and works with Jasmine, Jest, and Mocha.
* [tape](https://github.com/substack/tape)
* [TestCafe](http://devexpress.github.io/testcafe/) - a pure node.js end-to-end solution for testing web apps. It takes care of all the stages: starting browsers, running tests, gathering test results and generating reports.
* [Testem](https://github.com/testem/testem)

### Debug <a name="debug"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [ndb](https://github.com/GoogleChromeLabs/ndb) - an improved debugging experience for Node.js, enabled by Chrome DevTools.
* [stacktrace.js](https://www.stacktracejs.com/) - generate, parse, and enhance JavaScript stack traces in all web browsers.
* [Vorlon.JS](http://www.vorlonjs.com/) - an open source, extensible, platform-agnostic tool for remotely debugging and testing your JavaScript, powered by node.js and socket.io.
* [weinre](https://people.apache.org/~pmuellr/weinre/docs/latest/) - a debugger for web pages, like FireBug (for FireFox) and Web Inspector (for WebKit-based browsers), except it's designed to work remotely, and in particular, to allow you debug web pages on a mobile device such as a phone.
* [Wireshark](https://www.wireshark.org/) - the world’s foremost and widely-used network protocol analyzer.
* Use `new Error().stack` or `console.trace()` to print stack trace (see [Force Stack Traces with JavaScript](https://davidwalsh.name/javascript-stack-trace)).

### Documentation <a name="documentation"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [docsify](https://docsify.js.org/) - A magical documentation site generator.
* [documentation.js](http://documentation.js.org/) - The documentation system for modern JavaScript.
* [Docusaurus](https://docusaurus.io/) - A project for easily building, deploying, and maintaining open source project websites.
* [Docute](https://docute.org/) - The fastest way to create a documentation site for your project.
* [Docz](https://www.docz.site/) - It has never been so easy to document your things!
* [ESDoc](https://esdoc.org/) - A documentation generator for JavaScript (ES6).
* [JSDoc](http://usejsdoc.org/) - An API documentation generator for JavaScript.
* [x0](https://compositor.io/x0/) - Document & develop React components without breaking a sweat.
* [YUIDoc](http://yui.github.io/yuidoc/) - A Node.js application that generates API documentation from comments in source, using a syntax similar to tools like Javadoc and Doxygen.

### Code processing <a name="code-processing"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Prettier](https://prettier.io/) - an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

### Minification <a name="mini"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Minify](http://coderaiser.github.io/minify/) - a minifier of js, css, html and img files.
* [Node-minify](https://github.com/srod/node-minify) - a light Node.js module that compress javascript and css files.
* CSS
    - [clean-css](https://github.com/jakubpawlowicz/clean-css) - a fast and efficient CSS optimizer for Node.js platform and any modern browser.
    - [Crass](https://github.com/mattbasta/crass) - a CSS minification, pretty printing, and general utility library written in JS.
    - [cssnano](https://github.com/ben-eb/cssnano) - a modern, modular compression tool written on top of the PostCSS ecosystem.
    - [CSSO](https://github.com/css/csso) - a CSS minifier with structural optimizations.
    - [CSSWring](https://github.com/hail2u/node-csswring) - a CSS minifier for PostCSS.
* HTML
    - [HTMLMinifier](https://github.com/kangax/html-minifier) - a highly configurable, well-tested, JavaScript-based HTML minifier.
    - [Minimize](https://github.com/Swaagie/minimize) - a HTML minifier based on the node-htmlparser. Minimize is focussed on HTML5 and will not support older HTML drafts.
* Images
    - [Squoosh](https://squoosh.app/) - an image compression web app that allows you to dive into the advanced options provided by various image compressors.
    - [SVGO](https://github.com/svg/svgo) - a Nodejs-based tool for optimizing SVG vector graphics files.
* JavaScript
    - [Babel-Minify](https://github.com/babel/minify) - an ES6+ aware minifier based on the Babel toolchain.
    - [UglifyJS](https://github.com/mishoo/UglifyJS2) - a JavaScript parser, minifier, compressor and beautifier toolkit.

### Task runner, build tool <a name="task-runner"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Brunch](https://brunch.io/) - fast front-end web app build tool with simple declarative config, seamless incremental compilation for rapid development, an opinionated pipeline and workflow, and core support for source maps.
* [cross-env](https://github.com/kentcdodds/cross-env) - run scripts that set and use environment variables across platforms.
* [Grunion](https://github.com/Hypercubed/grunion) - run multiple commands using glob patterns.
* [Grunt](https://gruntjs.com/) - the JavaScript task runner.
* [Gulp](https://gulpjs.com/) - a toolkit for automating painful or time-consuming tasks in your development workflow.
* [Just](https://microsoft.github.io/just/) - a library that organizes build tasks for your JS projects. It consists of: a build task build definition library; sane preset build flows for node and browser projects featuring TypeScript, Webpack and jest; project scaffold tool that generates no-ejection needed repos that tracks template changes.
* [npm-run-all](https://github.com/mysticatea/npm-run-all) - a CLI tool to run multiple npm-scripts in parallel or sequential.
* [nps](https://github.com/kentcdodds/nps) - all the benefits of npm scripts without the cost of a bloated package.json and limits of json.
* [npx](https://github.com/zkat/npx) - execute npm package binaries.
* [Pkg](https://github.com/zeit/pkg) - this command line interface enables you to package your Node.js project into an executable that can be run even on devices without Node.js installed.
* [scripty](https://github.com/testdouble/scripty) - a tool to help extract npm scripts into their own files.
* [shx](https://github.com/shelljs/shx) - a wrapper around ShellJS Unix commands, providing an easy solution for simple Unix-like, cross-platform commands in npm package scripts.
* [Taskr](https://github.com/lukeed/taskr) - a fast, concurrency-focused task runner.
* [xclap](https://github.com/jchip/xclap) - an advanced and flexible JavaScript task executor and build tool.
* [ygor](https://github.com/shannonmoeller/ygor) - JavaScript task runner for when `npm run` isn't enough and everything else is too much.

### Automation <a name="automation"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [np](https://github.com/sindresorhus/np) - a better `npm publish`.

### Boilerplate, scaffolding <a name="boilerplate"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Create React App](https://github.com/facebook/create-react-app) - create React apps with no build configuration.
* [create-react-library](https://github.com/transitive-bullshit/create-react-library) - CLI for easily creating reusable react libraries.
* [nwb](https://github.com/insin/nwb) - a toolkit for React, Preact, Inferno & vanilla JS apps, React libraries and other npm modules for the web, with no configuration (until you need it).

### Component development <a name="component-dev"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [BlueKit](http://bluekit.blueberry.io/) - automatically generates a library from your React components with editable props and live preview.
* [component-playground](https://github.com/FormidableLabs/component-playground) - a component for rendering React Components and ES6 code with editable source and live preview.
* [Kit](https://compositor.io/kit/) - tools for developing, documenting, and testing React component libraries.
* [React Cosmos](https://github.com/react-cosmos/react-cosmos) - dev tool for creating reusable React components.
* [React Live](https://github.com/FormidableLabs/react-live) - brings you the ability to render React components and present the user with editable source code and live preview.
* [React Styleguidist](https://react-styleguidist.js.org/) - isolated React component development environment with a living style guide.
* [Storybook](https://storybook.js.org/) - a development environment for UI components. It allows you to browse a component library, view the different states of each component, and interactively develop and test components.

### Design <a name="design"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Playroom](https://github.com/seek-oss/playroom) - Simultaneously design across a variety of themes and screen sizes, powered by JSX and your own component library. Playroom allows you to create a zero-install code-oriented design environment, built into a standalone bundle that can be deployed alongside your existing design system documentation.

### Images, icons <a name="images"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Eva Icons](https://akveo.github.io/eva-icons/) - a pack of more than 480 beautifully crafted Open Source icons for common actions and items. Icons are provided in two visual types: Fill and Outline and in several formats, including PNG, SVG, font, Sketch, etc.
* [Ikonate](https://www.ikonate.com/) - fully customisable & accessible, well-optimised vector icons.
* [Super Tiny Icons](https://github.com/edent/SuperTinyIcons) - miniscule SVG versions of your favourite website and app logos.
* [SVG Porn](https://svgporn.com/) - a huge collection of SVG logos.

### Analysis, performance, optimization <a name="analysis"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Bundle Buddy](https://github.com/samccone/bundle-buddy) - a tool to help you find source code duplication across your javascript chunks/splits.
* [Lighthouse](https://developers.google.com/web/tools/lighthouse/) - an open-source, automated tool for improving the quality of web pages. It has audits for performance, accessibility, progressive web apps, and more.
* [Optimize your libraries with webpack](https://github.com/GoogleChromeLabs/webpack-libs-optimizations) - tips to make your webpack bundle smaller.
* [Size Limit](https://github.com/ai/size-limit) - calculate the real cost of your JS for end users and throws an error if the cost exceeds the limit.
* [Source map explorer](https://github.com/danvk/source-map-explorer) - analyze and debug space usage through source maps. The source map explorer determines which file each byte in your minified code came from.
* [Webpack Bundle Analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) - webpack plugin and CLI utility that represents bundle content as convenient interactive zoomable treemap.
* [WebPagetest](https://www.webpagetest.org/) - run a free website speed test from multiple locations around the globe using real browsers and at real consumer connection speeds.

### Version control <a name="version-control"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* Git <a name="git"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
    - [Git Extras](https://github.com/tj/git-extras) - Git utilities -- repo summary, repl, changelog population, author commit percentages and more.
    - [Husky](https://github.com/typicode/husky) - Git hooks made easy. Husky can prevent bad git commit, git push and more.
    - [Sourcetree](https://www.sourcetreeapp.com/) - visualize and manage your repositories through simple Git GUI.
    - [TortoiseGit](https://tortoisegit.org/) - a Windows Shell Interface to Git. Provides overlay icons showing the file status, a powerful context menu for Git and much more.

### Development server <a name="dev-server"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* Node.js-based <a name="dev-server-node"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
    - [Browsersync](https://www.browsersync.io/) - keep multiple browsers & devices in sync when building websites.
    - [EasyMock Server](https://github.com/cyberagent/node-easymock) - a simple but powerful mock server.
    - [freddie](https://github.com/Scytl/freddie) - front end development server.
    - [http-server](https://github.com/indexzero/http-server) - a simple, zero-configuration command-line http server.
    - [JSON Server](https://github.com/typicode/json-server) - get a full fake REST API with zero coding.
    - [Live Server](http://tapiov.net/live-server/) - a simple development http server with live reload capability.
    - [lite-server](https://github.com/johnpapa/lite-server) - lightweight development only node server that serves a web app. `lite-server` is a simple customized wrapper around BrowserSync to make it easy to serve SPAs.
    - [local-web-server](https://github.com/lwsjs/local-web-server) - the modular web server for productive full-stack development.
    - [MockIt](https://mockit.netlify.com/) - a tool to quickly create mocked APIs.
    - [Puer](https://github.com/leeluolee/puer) - more than a live-reload server , built for efficient frontend development.
    - [servedir](https://github.com/evanw/servedir) - a simple Node web server for offline development and testing: running servedir from a directory will create a quick local web server.
    - [server-with-benefits](https://github.com/galbi101/server-with-benefits) - a static Node.js file web server with options for proxing requests and delaying/mocking responses.
    - [Superstatic (with proxy)](https://github.com/colinbate/superstatic-with-proxy) - an enhanced static web server that was built to power. This version adds in the `superstatic-proxy` by default.
* With PHP support <a name="dev-server-php"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
    - [AppServ](http://www.appservnetwork.com) - a full-featured of Apache, MySQL, PHP, phpMyAdmin.
    - [Devserver](http://www.easyphp.org) - a complete and ready-to-use development environment. Devserver is portable, modular, fully configurable and easy to update and extend.
    - [Uniform Server](http://www.uniformserver.com/) - a lightweight server solution for running a web server under the WindowsOS.
    - [UwAmp](http://www.uwamp.com/en/) - free Wamp Server with Apache MySQL PHP and SQLite.
    - [VertrigoServ](http://vertrigo.sourceforge.net/) - a complete free WAMP server allowing PHP development for Windows.
    - [WampServer](http://www.wampserver.com/en/) - a Windows web development environment. It allows you to create web applications with Apache2, PHP and a MySQL database.
    - [WPИ-XM](http://wpn-xm.org/) - a free and open-source web server solution stack for professional PHP development on Windows.
    - [WTServer](http://wtserver.wtriple.com/) - a portable, preconfigured, lightweight, fast and stable server stack for developing php mysql applications on windows, based on the excellent webserver Nginx.
    - [XAMPP](https://www.apachefriends.org) - a completely free, easy to install Apache distribution containing MariaDB, PHP, and Perl.

### Node.js version management <a name="node-manage"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [n](https://github.com/tj/n) - interactively manage your Node.js versions.
* [node package](https://www.npmjs.com/package/node) - npm package that installs a `node` binary into your project, which means you can have a local version of `node` that is different than your system's, and manage `node` as a normal dependency.
* [nodenv](https://github.com/nodenv/nodenv) - manage multiple NodeJS versions.
* [Nodist](https://github.com/marcelklehr/nodist) - a node.js and npm version manager for the windows.
* [nvm (Node Version Manager)](https://github.com/creationix/nvm) - simple bash script to manage multiple active node.js versions.
* [nvm-windows](https://github.com/coreybutler/nvm-windows) - a node.js version management utility for Windows.
* [nvs (Node Version Switcher)](https://github.com/jasongin/nvs) - a cross-platform utility for switching between different versions and forks of Node.js. NVS is itself written in node JavaScript.

### Editor, IDE <a name="editor"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Atom](https://atom.io/) - a text editor that's modern, approachable, yet hackable to the core—a tool you can customize to do anything but also use productively without ever touching a config file.
* [Brackets](http://brackets.io/) - with focused visual tools and preprocessor support, Brackets is a modern text editor that makes it easy to design in the browser. It's crafted from the ground up for web designers and front-end developers.
* [Geany](https://www.geany.org/) - a small and lightweight Integrated Development Environment.
* [Light Table](http://lighttable.com/) - a next generation code editor that connects you to your creation with instant feedback. Light Table is very customizable and can display anything a Chromium browser can.
* [Notepad++](https://notepad-plus-plus.org/) - a free source code editor and Notepad replacement that supports several languages.
* [PSPad](https://www.pspad.com/) - text editor for developers for Microsoft Windows systems.
* [Visual Studio Code](https://code.visualstudio.com/) - a new type of tool that combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. Code provides comprehensive editing and debugging support, an extensibility model, and lightweight integration with existing tools.

### API <a name="api"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [APIs.guru](https://apis.guru/browse-apis/) - Wikipedia for WEB APIs.
* [ProgrammableWeb API directory](https://www.programmableweb.com/apis/directory) - directory where developers can search for APIs to include in their next software development project.
* [Public APIs](https://github.com/toddmotto/public-apis) - a collective list of free APIs for use in web development. 

### Playground, online development <a name="playground"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [CodePen](https://codepen.io/) - a playground for the front end side of the web. It's a place to build and deploy a website, show off your work, build test cases, and find inspiration.
* [CodeSandbox](https://codesandbox.io/) - an online web application editor. Makes it easier to create, share and reuse web projects with others.
* [ESNextbin](https://esnextb.in/) - create browser programs in ES2015 code and import modules from NPM in browser.
* [Flems.io](https://flems.io/) - a playground for web development. It's ideal for prototyping ideas & sharing working front-end code examples. Also see [Flems module](https://github.com/porsager/flems) which can be used for easy self hosting or embedding.
* [Glitch](https://glitch.com/) - the friendly community where everyone can discover and create the best stuff on the web.
* [JS Bin](https://jsbin.com/) - an open source collaborative web development debugging tool. Write code and have it both save in real-time, but also render a full preview in real-time.
* [jsFiddle](https://jsfiddle.net/) - an online playground for your JavaScript, HTML, CSS.
* [Repl.it](https://repl.it/) - simple, reliable, and portable cloud coding interface. A community of teachers, students and engineers.
* [RequireBin](http://requirebin.com/) - create programs in the browser using modules from NPM.
* [RunKit](https://runkit.com/) - a node playground in your browser.
* [Webpackbin](https://www.webpackbin.com/) - a service to share and teach code, using webpack to bundle the code.

### Site generator <a name="site-generator"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [CMS.js](http://chrisdiana.github.io/cms.js/) - fully client-side, Javascript site generator in the spirit of Jekyll that uses plain ol' HTML, CSS and Javascript to generate your website.
* [DocPad](http://docpad.org) - a dynamic static-site generator. That is a content management system that takes content from several sources, like files on your computer, and renders them into incredibly fast static output.
* [Gatsby](https://www.gatsbyjs.org/) - blazing-fast static site generator for React.
* [Hexo](https://hexo.io/) - a fast, simple and powerful blog framework. You write posts in Markdown (or other languages) and Hexo generates static files with a beautiful theme in seconds.

### Emulator, simulator <a name="emulator"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Responsinator](https://www.responsinator.com/) - helps website makers quickly get an indication of how their responsive site will look on the most popular devices.
* [Screenfly](http://quirktools.com/screenfly/) - allows you to view your website on a variety of device screens and resolutions.

### Browser extension <a name="browser-extension"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* Chrome
  - [25 Essential Chrome Extensions for Web Designers](https://envato.com/blog/chrome-extensions-web-design/)
  - [Checkbot](https://www.checkbot.io/) - crawls your site testing pages follow 50+ SEO, speed and security best practices.
  - [CSS Peeper](https://csspeeper.com/) - Smart CSS viewer tailored for Designers.
  - [JS Bundle Size](https://github.com/vicrazumov/js-bundle-size) - Automatically adds javascript bundle size data to npm and github project pages.

### Benchmark <a name="benchmark"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [CSS minification benchmark](http://goalsmashers.github.io/css-minification-benchmark/)
* [JS web frameworks benchmark](https://github.com/krausest/js-framework-benchmark) - a comparison of the perfomance of popular javascript frameworks.
* [UI Benchmark](https://localvoid.github.io/uibench/)

### Hosting, cloud services <a name="hosting"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [000webhost](https://www.000webhost.com/) & [hostinger.ru](https://www.hostinger.ru/) - zero cost website hosting with PHP, MySQL, Cpanel & no ads.
* [5apps Deploy](https://5apps.com/deploy/) - a turn-key deployment and hosting platform for client-side web apps.
* [Appback](https://appback.com/) - provides a backend as a service (BaaS) for web and mobile applications.
* [Backendless](https://backendless.com/) - a leading mBaaS and powerful Mobile Application Development Platform that enables rapid development of feature-rich mobile, desktop and browser-based applications.
* [Cloudant](https://www.ibm.com/cloud/cloudant) - a highly scalable and performant JSON database.
* [Cloudnode](https://cloudno.de/) - a place to get your Javascript web applications up and running.
* [Firebase](https://firebase.google.com/) - a cloud-hosted database. Data is synchronized in realtime to every connected client.
* [HackMD](https://hackmd.io/) - best way to share knowledge in markdown.
* [Heroku](https://www.heroku.com/) - a cloud platform that lets companies build, deliver, monitor and scale apps.
* [JSONbin](https://jsonbin.io/) - a free JSON storage and JSON hosting service.
* [Microsoft Azure](https://azure.microsoft.com/en-us/services/app-service/) - quickly create powerful cloud apps for web and mobile clients.
* [Modulus](https://modulus.io/) - application container platform. Deploy, scale, and monitor apps in the language of your choice.
* [Myjson](http://myjson.com/) - a simple JSON store for use in your client side web and/or mobile applications.
* [Netlify](https://www.netlify.com/) - builds, deploys, and hosts your front end.
* [now](https://zeit.co/now) - allows you to take your JavaScript (Node.js) or Docker powered websites, applications and services to the cloud with ease, speed and reliability.
* [Nuclino](https://www.nuclino.com/) - the easiest way to organize and share knowledge in teams. Create real-time collaborative documents and connect them instantly like a wiki. Use the tree, board, and graph view to explore and organize your knowledge visually. It's great for meeting notes, product requirements, docs, decisions, and more.
* [OpenShift](https://www.openshift.com/) - Red Hat's Platform-as-a-Service (PaaS) that allows developers to quickly develop, host, and scale applications in a cloud environment.
* [Pastebin](https://pastebin.com/) - a website where you can store any text online for easy sharing.
* [Rentry.co](https://rentry.co/) - a pastebin/publishing service with markdown support, preview, custom urls and editing. Fast, simple and free.
* [Surge](http://surge.sh/) - static web publishing for front-end developers.

### Guide, reference, practices, recipes <a name="guide"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [30 seconds of code](https://30secondsofcode.org/) - curated collection of useful JavaScript snippets that you can understand in 30 seconds or less.
* [30 Seconds of CSS](https://atomiks.github.io/30-seconds-of-css/) - a curated collection of useful CSS snippets you can understand in 30 seconds or less.
* [30 Seconds of Interviews](https://30secondsofinterviews.org/) - a curated collection of common interview questions to help you prepare for your next interview.
* [33 Concepts Every JavaScript Developer Should Know](https://github.com/leonardomso/33-js-concepts) - this repository was created with the intention of helping developers master their concepts in JavaScript. It is not a requirement, but a guide for future studies.
* [Checkbot: Web Best Practices](https://www.checkbot.io/guide/) - details 50+ SEO, speed and security web best practices.
* [CSS Protips](https://github.com/AllThingsSmitty/css-protips) - a collection of tips to help take your CSS skills pro.
* [CSS-Tricks](https://css-tricks.com/) - a site about all things web design and development.
* [DevDocs](https://devdocs.io/) - combines multiple API documentations in a fast, organized, and searchable interface.
* [Every Programmer Should Know](https://github.com/mtdvio/every-programmer-should-know) - a collection of (mostly) technical things every software developer should know.
* [Front End Interview Handbook](https://github.com/yangshun/front-end-interview-handbook) - almost complete answers to "Front-end Job Interview Questions" which you can use to interview potential candidates, test yourself or completely ignore.
* [Front-end Job Interview Questions](https://h5bp.github.io/Front-end-Developer-Interview-Questions/) - a list of helpful front-end related questions you can use to interview potential candidates or test yourself.
* [Grab Front End Guide](https://github.com/grab/front-end-guide) - study guide and introduction to the modern front end stack.
* [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms) - JavaScript based examples of many popular algorithms and data structures.
* [JavaScript Garden](http://bonsaiden.github.io/JavaScript-Garden/) - a growing collection of documentation about the most quirky parts of the JavaScript programming language.
* [Modern JS Cheatsheet](https://mbeaudru.github.io/modern-js-cheatsheet/) - cheatsheet for the JavaScript knowledge you will frequently encounter in modern projects.
* [Node.js Best Practices](https://github.com/i0natan/nodebestpractices) - a summary and curation of the top-ranked content on Node JS best practices.
* [OverAPI.com](http://overapi.com/) - collecting all cheat sheets.
* [Project Guidelines](https://github.com/elsewhencode/project-guidelines) - a list of guidelines that works really well with most JavaScript projects.
* [Service Worker Cookbook](https://serviceworke.rs/) - a collection of working, practical examples of using service workers in modern web sites.
* [Spellbook of Modern Web Dev](https://github.com/dexteryy/spellbook-of-modern-webdev) - a big picture, thesaurus, and taxonomy of modern JavaScript web development.
* [Tech Interview Handbook](https://github.com/yangshun/tech-interview-handbook) - carefully curated content to help you ace your next technical interview, with a focus on algorithms.

### Books <a name="books"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Data Structures and Algorithms in JavaScript](https://github.com/amejiarosario/dsa.js-data-structures-and-algorithms-in-javascript) - data structures and algorithms explained and implemented in JavaScript.
* [Freely available programming books](https://github.com/vhf/free-programming-books) - list of free learning resources.
* [Front-End Developer Handbook](https://frontendmasters.com/books/front-end-handbook/2018/) - a guide that anyone could use to learn about the practice of front-end development.
* [How to be a Programmer](https://www.gitbook.com/book/braydie/how-to-be-a-programmer/)
* [JavaScript Allongé](https://leanpub.com/javascriptallongesix/read) - a book about programming with functions.
* [React in patterns](https://legacy.gitbook.com/book/krasimir/react-in-patterns/details) - a book about common design patterns used while developing with React. It includes techniques for composition, data flow, dependency management and more.
* [SurviveJS](https://survivejs.com/) - books about React, Webpack and maintenance of JavaScript code.
* [The Complete JavaScript Handbook](https://medium.freecodecamp.org/the-complete-javascript-handbook-f26b2c71719c) - learn 80% of JavaScript in 20% of the time.

### Examples <a name="examples"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [CSSFX](https://cssfx.dev/) - beautifully simple click-to-copy CSS effects. A carefully crafted collection designed with a focus on fluidity, simplicity, and ease of use. Powered by CSS with minimal markup.
* [Hacker News readers as Progressive Web Apps](https://hnpwa.com/) - a list of unofficial Hacker News clients built with a number of popular JavaScript frameworks and libraries. Each implementation is a complete Progressive Web App that utilizes different progressive technologies to provide a fast, reliable and engaging experience.
* [simpl.info](https://simpl.info/) - simplest possible examples of HTML, CSS and JavaScript.

### Useful articles & resources <a name="resources"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [120+ Places To Find Creative Commons Media](https://www.sitepoint.com/creative-commons-sources/) - resources to search for audio, video, images and more for use in a project.
* [The cost of small modules](https://nolanlawson.com/2016/08/15/the-cost-of-small-modules/) - demonstrates that small modules can have a surprisingly high performance cost depending on your choice of bundler and module system.
* [The cost of transpiling es2015 in 2016](https://github.com/samccone/The-cost-of-transpiling-es2015-in-2016)
* [What Do the Popular JavaScript Tools Depend On?](http://developer.telerik.com/featured/popular-javascript-tools-depend/)
* [Why Performance Matters](https://developers.google.com/web/fundamentals/performance/why-performance-matters/)

[Table of contents &#x2191;](#toc)
