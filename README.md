# Front-end development tools (mostly)

#### Table of contents <a name="toc"></a>
* [Tools catalog / search / discovery / comparison service](#tool-search)
* [ECMAScript / JavaScript](#ecmascript)
    - [Specification](#es-specification)
    - [Support / compatibility](#es-support)
    - [Documentation, guide](#es-doc)
* [JavaScript runtime](#js-runtime)
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
    - [Redux-based library](#redux-library)
* [Database](#database)
* [Internationalization (i18n), localization (l10n)](#i18n)
* [JavaScript utility library](#js-utility-library)
* [JavaScript module system and loader](#loader)
* [Module and asset bundler](#bundler)
* [Package manager](#package-manager)
* [CSS processor](#css-processor)
* [CSS tool](#css-tool)
* [Linting, validation, checklist](#linting)
* [Testing](#testing)
* [Debug](#debug)
* [Documentation](#documentation)
* [Code processing](#code-processing)
* [Minification](#mini)
* [Unminifier](#unmini)
* [Task runner, build tool](#task-runner)
* [Automation](#automation)
* [Boilerplate, scaffolding](#boilerplate)
* [Component development](#component-dev)
* [Design](#design)
* [Graphics/image editor](#image-editor)
* [Images, icons](#images)
* [Analysis, performance, optimization](#analysis)
* [Network](#net)
* [Version control](#version-control)
    - [Git](#git)
* [Development server](#dev-server)
    - [Node.js-based](#dev-server-node)
    - [With PHP support](#dev-server-php)
* [Node.js version management](#node-manage)
* [Editor, IDE](#editor)
* [Playground, interactive computing](#playground)
* [Online development/playground](#online-dev)
* [Online tool](#online-tool)
* [Site generator](#site-generator)
* [Emulator, simulator](#emulator)
* [API](#api)
* [Browser extension](#browser-extension)
* [Benchmark](#benchmark)
* [Hosting, cloud services](#hosting)
* [Code CDN](#code-cdn)
* [Guide, reference, practices, recipes](#guide)
    - [CSS](#css-guide)
    - [HTML](#html-guide)
    - [JavaScript](#js-guide)
    - [TypeScript](#ts-guide)
* [Books](#books)
* [Examples](#examples)
    - [CSS](#css-examples)
    - [HTML](#html-examples)
* [Useful articles & resources](#resources)

### Tools catalog / search / discovery / comparison service <a name="tool-search"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [AlternativeTo](https://alternativeto.net/) - a free service that helps you find better alternatives to the products you love and hate.
* [awesome](https://awesome.re/) - a curated list of awesome lists.
* [Awesome Open Source](https://awesomeopensource.com/) - find open source by searching, browsing and combining topics.
* [awesome-react-components](https://github.com/brillout/awesome-react-components) - curated list of React components & libraries.
* [Best of JavaScript](https://bestofjs.org/) - a place to find the best components to build amazing web applications.
* [CSS Script](https://www.cssscript.com/) - a Javascript & CSS code library aims to provide the newest, best and free CSS & javascript resources for web/mobile developers and designers.
* [Free for developers](https://free-for.dev/) - a list of software (SaaS, PaaS, IaaS, etc.) and other offerings that have free tiers for developers.
* [headlesscms.org](https://headlesscms.org/) - a list of content management systems for JAMstack sites.
* [iReact](http://ireact.cn/) - helps you discover the most fantastic, powerful React Components and Libraries, and makes it easy for you to pick one that’ll work for you.
* [JavaScripting](https://www.javascripting.com/) - the definitive source of the best JavaScript libraries, frameworks, and plugins.
* [jQuery Plugins](https://jquery-plugins.net/) - categorized collection of jQuery plugins.
* [JqueryScript.Net](https://www.jqueryscript.net/) - one of jQuery plugin websites that provide web designers and developers with a simple way to preview and download a variety of free jQuery plugins.
* [JSter](http://jster.net/) - a catalog of frontend JavaScript libraries.
* [JS.coach](https://js.coach/) - an opinionated catalog of open source JS packages.
* [LibHunt](https://www.libhunt.com/) -  our goal is to help you find the software and libraries you need. All lists have been crafted by many experts from the relevant GitHub communities.
* [Libraries.io](https://libraries.io/) - helps developers find new open source libraries, modules and frameworks and keep track of ones they depend upon.
* [MicroJS](http://microjs.com) - fantastic Micro-Frameworks and Micro-Libraries for Fun and Profit!
* [Moiva](https://moiva.io/) - measure and compare JavaScript libraries.
* [Node Frameworks](http://nodeframework.com/) - hand-picked registry of Node.js frameworks.
* [NPMCompare](https://npmcompare.com/) - search and compare npm packages.
* [npms](https://npms.io/) - a better and open source search for node modules.
* [npm trends](https://www.npmtrends.com/) - compare package download counts over time.
* [Openbase](https://openbase.com/) - a platform to help developers navigate the world of open-source and make more well-informed choices.
* [Pika](https://www.pika.dev/) - search npm for fast, modern packages.
* [Redux Ecosystem Links](https://github.com/markerikson/redux-ecosystem-links) - a categorized list of addon libraries for Redux, as well as other libraries that are closely related.
* [Slant](https://www.slant.co/) - a product recommendation community that helps connect people with the best products for them.
* [StackShare](https://stackshare.io/) - discover & discuss the best software tools & services.
* [StaticGen.com](https://www.staticgen.com/) - a leaderboard of top open-source static site generators.
* [Unheap](http://www.unheap.com/) - a tidy repository of JavaScript plugins.
* [VueScript.com](https://www.vuescript.com/) - aims to offer latest free Vue.js components for web application developers.
* [webcomponents.org](https://www.webcomponents.org/) - a place to publish, browse and search for reusable web UI components.

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

### JavaScript runtime <a name="js-runtime"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Deno](https://deno.land/) - a JavaScript/TypeScript runtime with secure defaults and a great developer experience.
* [Node.js](https://nodejs.org/) - an asynchronous event-driven JavaScript runtime designed to build scalable network applications.
* [Ringo](https://ringojs.org/) - a JavaScript platform built on the JVM and optimized for server-side applications.

### JavaScript variant / compiler / transpiler <a name="js-variant"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Babel](https://babeljs.io/) - a JavaScript compiler.
* [Bublé](https://buble.surge.sh/) - fast, batteries-included ES2015 compiler.
* [Sucrase](https://sucrase.io/) - super-fast alternative to Babel for when you can target modern JS runtimes.
* [swc](https://swc-project.github.io/) - a TypeScript / JavaScript compiler. It consumes a JavaScript or TypeScript file which uses recently added features and emits JavaScript code which can be executed on old browsers.
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
* [Alpine.js](https://github.com/alpinejs/alpine) - a rugged, minimal framework for composing JavaScript behavior in your markup. Alpine.js offers you the reactive and declarative nature of big frameworks like Vue or React at a much lower cost.
* [Cell](https://www.celljs.org/) - a self-constructing web app framework powered by a self-driving DOM.
* [Inferno](https://infernojs.org/) - an extremely fast, React-like JavaScript library for building modern user interfaces.
* [Marko](https://markojs.com/) - a friendly (and fast!) UI library that makes building web apps fun.
* [Melody](https://melody.js.org/) - a fast and memory efficient library for creating highly dynamic user interfaces.
* [Monkberry](https://monkberry.js.org/) - blazingly fast, small and simple JavaScript library for building web user interfaces.
* [Moon](https://moonjs.org/) - the minimal & fast library for functional user interfaces.
* [Nerv](https://github.com/NervJS/nerv) - a blazing fast React alternative, compatible with IE8 and React 16.
* [Preact](https://preactjs.com/) - fast 3kb alternative to React with the same ES6 API.
* [Ractive.js](https://ractive.js.org/) - a JavaScript library for building reactive user interfaces in a way that doesn't force you into a particular framework's way of thinking.
* [React](https://reactjs.org/) - a JavaScript library for building user interfaces.
* [Riot](https://riot.js.org/) - simple and elegant component-based UI library.
* [Solid](https://github.com/ryansolid/solid) - a declarative, efficient, and flexible JavaScript library for building user interfaces.
* [Svelte](https://svelte.dev/) - rather than interpreting your application code at run time, your app is converted into ideal JavaScript at build time.
* [Vue.js](https://vuejs.org/) - simple yet powerful library for building modern web interfaces.

### React-based library / framework / platform <a name="react-library"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Ant Design](https://ant.design/docs/react/introduce) - an enterprise-class UI design language and React-based implementation.
* [Blueprint](https://blueprintjs.com/) - a React-based UI toolkit for the web. It is optimized for building complex, data-dense web interfaces for desktop applications.
* [Chakra UI](https://chakra-ui.com/) - a simple, modular and accessible component library that gives you all the building blocks you need to build your React applications.
* [dva](https://github.com/dvajs/dva) - React and Redux based, lightweight and Elm-style framework.
* [Electrode](http://www.electrode.io/) - a platform for building universal React/Node.js applications with standardized structure, best practices, and modern technologies baked in.
* [Elemental UI](http://elemental-ui.com/) - a UI Toolkit for React.js Websites and Apps.
* [Fusion.js](https://fusionjs.com/) - modern framework for fast, powerful React apps. Fusion.js is a universal web framework that represents the fusion of the client and the server. It's geared for server-side rendering out of the box, and its plugin-driven architecture allows for complex frontend and backend logic to be encapsulated in a single plugin.
* [Grommet](https://grommet.io/) - a React-based framework that provides accessibility, modularity, responsiveness, and theming in a tidy package.
* [libreact](https://github.com/streamich/libreact) - a collection of most essential React utilities you will probably need in any project.
* [Material-UI](https://material-ui.com/) - a Set of React Components that Implement Google's Material Design.
* [react-md](https://react-md.dev/) - an accessible React component library built from the Material Design guidelines in Sass.
* [React Toolbox](http://react-toolbox.io) - a set of React components that implements Google Material Design specification.
* [ReactXP](https://microsoft.github.io/reactxp/) - a library for cross-platform app development using React and React Native.
* [Rebass](https://rebassjs.org/) - React primitive UI components built with Styled System.

### Vue-based library / framework <a name="vue-library"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [BalmUI](https://material.balmjs.com/) - next generation Material UI for Vue.js.
* [Buefy](https://buefy.org/) - a lightweight library of responsive UI components for Vue.js based on Bulma framework and design.
* [Element](http://element.eleme.io/) - a Vue.js 2.0 UI Toolkit for Web.
* [iView](https://www.iviewui.com/) - a high quality UI Toolkit built on Vue.js.
* [Keen UI](https://josephuspaye.github.io/Keen-UI/) - a lightweight collection of essential UI components written with Vue.js and inspired by Material Design.
* [Muse UI](https://museui.github.io/) - a Vue 2.0 and Material Design based UI component library.
* [Quasar Framework](https://quasar.dev/) - build high-performance VueJS user interfaces in record time.
* [Vuetify.js](https://vuetifyjs.com/) - a component framework for Vue.js 2.
* [Vue Material](https://vuematerial.io/) - simple, lightweight and built exactly according to the Google Material Design specs. Build well-designed apps that can fit on every screen with support to all modern Web Browsers with dynamic themes, components on demand and all with an ease-to-use API.

### Front-end / CSS framework <a name="frontend-framework"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [AgnosticUI](https://www.agnosticui.com/) - a UI component library designed to work with multiple JavaScript frameworks (React, Vue, Svelte, and Angular). 
* [Blaze](https://www.blazeui.com/) - an open source modular toolkit. It provides great structure for building websites quickly with a scalable and maintainable foundation.
* [Bootflat](http://bootflat.github.io/) - an open source Flat UI KIT based on Bootstrap 3.3.0 CSS framework.
* [Bootstrap](https://getbootstrap.com/) - an open source toolkit for developing with HTML, CSS, and JS.
* [Bulma](https://bulma.io/) - a modern CSS framework based on Flexbox.
* [Flat UI](http://designmodo.github.io/Flat-UI/) - a beautiful theme for Bootstrap.
* [Foundation](https://get.foundation/) - the most advanced responsive front-end framework in the world.
* [Froala Design Blocks](https://www.froala.com/design-blocks) - a set of 170+ Bootstrap based design blocks ready to be used to create clean modern websites.
* [GroundworkCSS](http://groundworkcss.github.io/) (outdated) - a fully responsive HTML5, CSS and Javascript toolkit.
* [Halfmoon](https://www.gethalfmoon.com/) - front-end framework with a built-in dark mode and full customizability using CSS variables; great for building dashboards and tools.
* [Ink](http://ink.sapo.pt/) - an interface kit for quick development of web interfaces, simple to use and expand on.
* [inuitcss](https://github.com/inuitcss/inuitcss) - extensible, scalable, Sass-based, OOCSS framework for large and long-lasting UI projects. It does not provide you with UI and design out of the box, instead, it provides you with a solid architectural baseline upon which to complete your own work.
* [Kube](https://imperavi.com/kube/) - clean, minimalistic and fast to implement CSS & JS framework for professional developers and designers alike.
* [Material Components for the web](https://github.com/material-components/material-components-web) - modular and customizable Material Design UI components for the web. Developed by a core team of engineers and UX designers at Google, these components enable a reliable development workflow to build beautiful and functional web projects.
* [Material Design Lite](https://getmdl.io/) - lets you add a Material Design look and feel to your websites. It doesn’t rely on any JavaScript frameworks and aims to optimize for cross-device use, gracefully degrade in older browsers, and offer an experience that is immediately accessible.
* [Material Framework](http://nt1m.github.io/material-framework/) - a simple responsive CSS framework that allows you to integrate Material Design in any web page or web app.
* [Materialize](https://materializecss.com/) - a modern responsive front-end framework based on Material Design.
* [Metro UI](https://metroui.org.ua/) - sleek, intuitive, and powerful front-end framework for faster and easier web development. Build responsive, mobile-first projects on the web with the first front-end component library in Metro Style.
* [Polymer](https://www.polymer-project.org/) - libraries, tools and patterns to help developers build modern Progressive Web Apps, taking full advantage of cutting-edge platform features like Web Components, Service Workers and HTTP/2.
* [Semantic UI](https://semantic-ui.com/) - a development framework that helps create beautiful, responsive layouts using human-friendly HTML.
* [Shorthand](https://shorthandcss.bansal.io/) - a free and open source css framework, that allows you to make unique and modern design without writing any css.
* [Spectre.css](https://picturepan2.github.io/spectre/) - a lightweight, responsive and modern CSS framework.
* [Tailwind CSS](https://tailwindcss.com/) - a utility-first CSS framework for rapid UI development.
* [Topcoat](http://topcoat.io/) - CSS for clean and fast web apps.
* [Turret](https://turretcss.com/) - a styles and browser behaviour normalisation framework for rapid development of responsive and accessible websites.
* [UIkit](https://getuikit.com/) - a lightweight and modular front-end framework for developing fast and powerful web interfaces.
* Small CSS library / toolkit <a name="small-css-library"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
    - [Basscss](https://basscss.com/) - low-Level CSS Toolkit, a lightweight collection of immutable utilities designed for speed, clarity, performance, and scalability.
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
* [NodeGui](https://nodegui.org/) - an open source library for building cross-platform native desktop applications with JavaScript and CSS like styling. NodeGui is based on Qt5 and NOT chromium, hence it is memory and cpu efficient. React NodeGui is a React renderer for NodeGui.
* [NW.js](https://nwjs.io/) - an app runtime based on Chromium and node.js. You can write native apps in HTML and JavaScript with NW.js.
* [Proton Native](https://proton-native.js.org/) - a React environment for cross platform native desktop apps.

### Data / model / state management library <a name="state-management"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Breeze](http://www.getbreezenow.com/breezejs) - the data management library for developers of rich client applications written in JavaScript. If you store data in a database, query and save those data as complex object graphs, and share these graphs across multiple screens of your JavaScript client, Breeze is for you.
* [Cerebral](https://cerebraljs.com/) - a declarative state and side effects management solution for popular JavaScript frameworks.
* [Effector](https://effector.now.sh/) - an effective multi-store state manager for Javascript apps, that allows you to manage data in complex applications without the risk of inflating the monolithic central store, with clear control flow, good type support and high capacity API.
* [freactal](https://github.com/FormidableLabs/freactal) - a composable state management library for React.
* [JSData](https://www.js-data.io/) - a framework-agnostic, datastore-agnostic ORM for Node.js and the Browser.
* [Microstates](https://github.com/microstates/microstates.js) - a functional runtime type system designed to ease state management in component based applications. It allows you to declaratively compose application state from atomic state machines.
* [MobX](https://mobx.js.org/) - a battle tested library that makes state management simple and scalable by transparently applying functional reactive programming.
* [NuclearJS](https://optimizely.github.io/nuclear-js/) - reactive Flux built with ImmutableJS data structures.
* [Orbit](https://orbitjs.com/) - a composable data framework for managing the complex needs of today's web applications. Although Orbit is primarily used as a flexible client-side ORM, it can also be used server-side in Node.js.
* [Overmind](https://overmindjs.org) - frictionless state management. Overmind aims for a developer experience where that is all you focus on, reducing the orchestration of state management to a minimum.
* [Redux](https://redux.js.org/) - a predictable state container for JavaScript apps.
* [Storeon](https://github.com/storeon/storeon) - a tiny event-based Redux-like state manager for React and Preact.
* [Transis](https://github.com/centro/transis) - a JavaScript data modeling library useful for creating rich client-side experiences.
* [Undux](https://undux.org/) - a simple & typesafe alternative to Flux and Redux. Use it to manage state and data for ReactJS applications of all sizes.
* [Unistore](https://github.com/developit/unistore) - a tiny centralized state container with component bindings for Preact & React.
* [WatermelonDB](https://nozbe.github.io/WatermelonDB/) - build powerful React and React Native apps that scale from hundreds to tens of thousands of records and remain fast.
* Redux-based library <a name="redux-library"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
    - [Easy Peasy](https://easy-peasy.now.sh/) - provides you with an intuitive API to quickly and easily manage the state for your React application. No configuration is required to support derived state, API calls, performance optimisation, developer tools etc.
    - [Kea](https://keajs.org/) - a production-grade state management framework built for React apps. Kea is built on top of Redux and leverages its underlying functional principles.
    - [Redux Toolkit](https://redux-toolkit.js.org/) - the official, opinionated, batteries-included toolset for efficient Redux development.
    - [Rematch](https://rematch.github.io/rematch/) - Redux best practices without the boilerplate.

### Database <a name="database"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [AlaSQL](http://alasql.org/) - JavaScript SQL database for browser and Node.js. Handles both traditional relational tables and nested JSON data (NoSQL). Export, store, and import data from localStorage, IndexedDB, or Excel.
* [DataScript](https://github.com/tonsky/datascript) - immutable database and Datalog query engine for Clojure, ClojureScript and JS.
* [ForerunnerDB](http://www.forerunnerdb.com) - a NoSQL JavaScript JSON database with a query language based on MongoDB (with some differences) and runs on browsers and Node.js.
* [LokiJS](https://github.com/techfort/LokiJS) - a document oriented database written in javascript. Its purpose is to store javascript objects as documents in a nosql fashion and retrieve them with a similar mechanism. Runs in node (including cordova/phonegap and node-webkit), nativescript and the browser.
* [Lowdb](https://github.com/typicode/lowdb) - a small local database for small projects (powered by lodash API).
* [nanoSQL](https://nanosql.io/) - universal database layer for the client, server & mobile devices. It's like Lego for databases. 
* [NeDB](https://github.com/louischatriot/nedb) - embedded persistent or in memory database for Node.js, nw.js, Electron and browsers, 100% JavaScript, no binary dependency.
* [PouchDB](https://pouchdb.com/) - an open-source JavaScript database inspired by Apache CouchDB that is designed to run well within the browser. It enables applications to store data locally while offline, then synchronize it with CouchDB and compatible servers when the application is back online, keeping the user's data in sync no matter where they next login.
* [RxDB](https://rxdb.info/) - a realtime database for JavaScript applications. RxDB is a NoSQL-database for JavaScript applications like websites, hybrid apps, Electron-apps, Progressive Web Apps and NodeJs.
* [TingoDB](http://www.tingodb.com/) - an embedded JavaScript in-process filesystem or in-memory database upwards compatible with MongoDB at the API level.

### Internationalization (i18n), localization (l10n) <a name="i18n"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Fluent.js](https://github.com/projectfluent/fluent.js) - a JavaScript implementation of [Project Fluent](https://projectfluent.org/), a localization framework designed to unleash the expressive power of the natural language.
* [FormatJS](https://formatjs.io/) - a modular collection of JavaScript libraries for internationalization that are focused on formatting numbers, dates, and strings for displaying to people. It includes a set of core libraries that build on the JavaScript Intl built-ins and industry-wide i18n standards, plus a set of integrations for common template and component libraries.
* [Globalize](https://globalizejs.com/) - a JavaScript library for internationalization and localization that leverage the official Unicode CLDR JSON data. Globalize provides number formatting and parsing, date and time formatting and parsing, currency formatting, message formatting (ICU message format pattern), and plural support.
* [i18next](https://www.i18next.com/) - an internationalization-framework written in and for JavaScript. It provides you with a complete solution to localize your product from web to mobile and desktop.
* [Lingui](https://lingui.js.org/) - an easy yet powerfull internationalization framework for global projects.

### JavaScript utility library <a name="js-utility-library"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [101](https://github.com/tjmehta/101) - a modern JS utility library.
* [Licia](https://licia.liriliri.io/) - useful utility collection with zero dependencies.
* [Lodash](https://lodash.com/) - a modern JavaScript utility library delivering modularity, performance & extras.
* [Mout](http://moutjs.com/) - a collection of modular JavaScript utilities that can be used in the browser as AMD modules or on node.js.
* [Sugar](https://sugarjs.com/) - a Javascript utility library for working with native objects.
* [Umbrella](https://github.com/thi-ng/umbrella/) - a collection of functional programming libraries that can be composed together.
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
    - [Snowpack](https://www.snowpack.dev/) - with Snowpack you can build modern web apps (using React, Vue, etc.) without a bundler (like Webpack, Parcel, Rollup). No more waiting for your bundler to rebuild your site. Instead, every change is reflected in the browser instantly.

### Module and asset bundler <a name="bundler"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Browserify](http://browserify.org/) - lets you `require('modules')` in the browser by bundling up all of your dependencies.
* [esbuild](https://esbuild.github.io/) - an extremely fast JavaScript bundler.
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
* [Yarn](https://yarnpkg.com/) - fast, reliable, and secure dependency management.

### CSS processor <a name="css-processor"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [EQCSS](http://elementqueries.com/) - A CSS Extension for Element Queries & More.
* [Less](http://lesscss.org/) - The dynamic stylesheet language.
* [PostCSS](http://postcss.org/) - A tool for transforming CSS with JavaScript.
* [Sass](http://sass-lang.com/) - An extension of CSS, adding nested rules, variables, mixins, selector inheritance, and more. 
* [Stylus](http://stylus-lang.com/) - Expressive, robust, feature-rich language, providing an efficient, dynamic, and expressive way to generate CSS. 

### CSS tool <a name="css-tool"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Change SVG Color](https://change-svg-color.edrini.xyz/) ([Github](https://github.com/Prottoy2938/change-svg-color)) - converts Hex, Rgba, HSLA color to CSS filter. And the CSS filter could be used to change the SVG color.
* [CSS Gradient](https://cssgradient.io/) - a website and free tool that lets you create a gradient background for websites.
* [Keyframes](https://keyframes.app/) - a free bundle of tools to generate & live preview different CSS properties, plus some other web development tools.
* [Smooth Shadow](https://shadows.brumm.af/) - make a smooth shadow.

### Linting, validation, checklist <a name="linting"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Front-End Checklist](https://frontendchecklist.io/) - an exhaustive list of all elements you need to have / to test before launching your site / HTML page to production.
* [lint-staged](https://github.com/okonet/lint-staged) - run linters against staged git files. This project contains a script that will run arbitrary shell tasks with a list of staged files as an argument, filtered by a specified glob pattern.
* [textlint](https://textlint.github.io/) - the pluggable linting tool for text and markdown. `textlint` is similar to `ESLint`, but it's for use with natural language.
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
    - [unimported](https://github.com/smeijer/unimported) - find and fix dangling files and unused dependencies in your JavaScript projects. 
    - [XO](https://github.com/xojs/xo) - opinionated but configurable ESLint wrapper with lots of goodies included.

### Testing <a name="testing"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [AVA](https://github.com/avajs/ava) - a test runner for Node.js with a concise API, detailed error output, embrace of new language features and process isolation that let you write tests more effectively.
* [BackstopJS](https://garris.github.io/BackstopJS/) - automates visual regression testing of your responsive web UI by comparing DOM screenshots over time.
* [Chai](https://www.chaijs.com/) - a BDD / TDD assertion library for node and the browser that can be delightfully paired with any javascript testing framework.
* [CodeceptJS](https://codecept.io/) - acceptance testing framework for NodeJS. CodeceptJS is a testing framework for end-to-end testing with WebDriver (or others). It abstracts browser interaction to simple steps which is written from a user perspective.
* [Cypress](https://www.cypress.io/) - a test engine that runs unit and integration tests in your browser.
* [Enzyme](https://enzymejs.github.io/enzyme/) - a JavaScript Testing utility for React that makes it easier to test your React Components' output. You can also manipulate, traverse, and in some ways simulate runtime given the output.
* [Gauge](https://gauge.org/) - a light weight cross-platform test automation tool. It provides the ability to author test cases in the business language.
* [Intern](https://theintern.io/) - a complete test system for JavaScript designed to help you write and run consistent, high-quality test cases for your JavaScript libraries and applications.
* [Istanbul](https://istanbul.js.org/) - JS code coverage tool that computes statement, line, function and branch coverage.
* [Jasmine](https://jasmine.github.io/) - a behavior-driven development framework for testing JavaScript code.
* [Jest](https://jestjs.io/) - a delightful JavaScript Testing Framework with a focus on simplicity.
* [Karma](http://karma-runner.github.io/) - a tool that allows you to execute JavaScript code in multiple real browsers.
* [Majestic](https://github.com/Raathigesh/majestic) - zero config GUI for Jest.
* [Mocha](https://mochajs.org/) - simple, flexible, fun JavaScript test framework for Node.js & The Browser.
* [Mock Service Worker](https://github.com/mswjs/msw) - an API mocking library for browser and Node.js.
* [QA Wolf](https://www.qawolf.com/) - a Node.js library for creating browser tests.
* [QUnit](https://qunitjs.com/) - a powerful, easy-to-use JavaScript unit testing framework.
* [Sazerac](https://sazerac.js.org/) - data-driven testing for JavaScript. It helps you create simple, readable tests and works with Jasmine, Jest, and Mocha.
* [tape](https://github.com/substack/tape) - tap-producing test harness for node and browsers.
* [TestCafe](https://devexpress.github.io/testcafe/) - a node.js tool to automate end-to-end web testing.
* [Testem](https://github.com/testem/testem) - a test runner that makes Javascript unit testing fun.
* [Testing Library](https://testing-library.com/) - simple and complete testing utilities that encourage good testing practices and help you test UI components in a user-centric way.

### Debug <a name="debug"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Eruda](https://eruda.liriliri.io/) - console for mobile browsers.
* [fuite](https://github.com/nolanlawson/fuite) - a CLI tool for finding memory leaks in web apps.
* [ndb](https://github.com/GoogleChromeLabs/ndb) - an improved debugging experience for Node.js, enabled by Chrome DevTools.
* [stacktrace.js](https://www.stacktracejs.com/) - generate, parse, and enhance JavaScript stack traces in all web browsers.
* [Vorlon.JS](http://www.vorlonjs.com/) - an open source, extensible, platform-agnostic tool for remotely debugging and testing your JavaScript, powered by node.js and socket.io.
* [weinre](https://people.apache.org/~pmuellr/weinre/docs/latest/) - a debugger for web pages, like FireBug (for FireFox) and Web Inspector (for WebKit-based browsers), except it's designed to work remotely, and in particular, to allow you debug web pages on a mobile device such as a phone.
* Use `new Error().stack` or `console.trace()` to print stack trace (see [Force Stack Traces with JavaScript](https://davidwalsh.name/javascript-stack-trace)).

### Documentation <a name="documentation"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [docsify](https://docsify.js.org/) - A magical documentation site generator.
* [documentation.js](http://documentation.js.org/) - The documentation system for modern JavaScript.
* [Docusaurus](https://docusaurus.io/) - A project for easily building, deploying, and maintaining open source project websites.
* [Docute](https://docute.org/) - The fastest way to create a documentation site for your project.
* [Docz](https://www.docz.site/) - It has never been so easy to document your things!
* [ESDoc](https://esdoc.org/) - A documentation generator for JavaScript (ES6).
* [JSDoc](http://usejsdoc.org/) - An API documentation generator for JavaScript.
* [x0](https://github.com/c8r/x0) - Document & develop React components without breaking a sweat.
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
    - [CompressImage.io](https://compressimage.io/) - compress JPG and PNG images at light speed with browser based image compressor. Private, works offline.
    - [Compressor.io](https://compressor.io/) - fast & efficient online image compression.
    - [Squoosh](https://squoosh.app/) - an image compression web app that allows you to dive into the advanced options provided by various image compressors.
    - [SVGO](https://github.com/svg/svgo) - a Nodejs-based tool for optimizing SVG vector graphics files.
* JavaScript
    - [Babel-Minify](https://github.com/babel/minify) - an ES6+ aware minifier based on the Babel toolchain.
    - [UglifyJS](https://github.com/mishoo/UglifyJS2) - a JavaScript parser, minifier, compressor and beautifier toolkit.

### Unminifier <a name="unmini"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [unminify](https://unminify.com/) - free tool to unminify (unpack, deobfuscate) JavaScript, CSS, HTML, XML and JSON code, making it readable and pretty.

### Task runner, build tool <a name="task-runner"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Brunch](https://github.com/brunch/brunch) - fast front-end web app build tool with simple declarative config, seamless incremental compilation for rapid development, an opinionated pipeline and workflow, and core support for source maps.
* [cross-env](https://github.com/kentcdodds/cross-env) - run scripts that set and use environment variables across platforms.
* [Grunion](https://github.com/Hypercubed/grunion) - run multiple commands using glob patterns.
* [Grunt](https://gruntjs.com/) - the JavaScript task runner.
* [Gulp](https://gulpjs.com/) - a toolkit for automating painful or time-consuming tasks in your development workflow.
* [Just](https://microsoft.github.io/just/) - a library that organizes build tasks for your JS projects. It consists of: a build task build definition library; sane preset build flows for node and browser projects featuring TypeScript, Webpack and jest; project scaffold tool that generates no-ejection needed repos that tracks template changes.
* [ncc](https://github.com/zeit/ncc) - simple CLI for compiling a Node.js module into a single file, together with all its dependencies, gcc-style.
* [nexe](https://github.com/nexe/nexe) - a command-line utility that compiles your Node.js application into a single executable file.
* [npm-run-all](https://github.com/mysticatea/npm-run-all) - a CLI tool to run multiple npm-scripts in parallel or sequential.
* [nps](https://github.com/kentcdodds/nps) - all the benefits of npm scripts without the cost of a bloated package.json and limits of json.
* [npx](https://github.com/npm/npx) - execute npm package binaries.
* [Pkg](https://github.com/zeit/pkg) - this command line interface enables you to package your Node.js project into an executable that can be run even on devices without Node.js installed.
* [scripty](https://github.com/testdouble/scripty) - a tool to help extract npm scripts into their own files.
* [shx](https://github.com/shelljs/shx) - a wrapper around ShellJS Unix commands, providing an easy solution for simple Unix-like, cross-platform commands in npm package scripts.
* [Taskr](https://github.com/lukeed/taskr) - a fast, concurrency-focused task runner.
* [xclap](https://github.com/jchip/xclap) - an advanced and flexible JavaScript task executor and build tool.
* [ygor](https://github.com/shannonmoeller/ygor) - JavaScript task runner for when `npm run` isn't enough and everything else is too much.

### Automation <a name="automation"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [np](https://github.com/sindresorhus/np) - a better `npm publish`.
* [semantic-release](https://github.com/semantic-release/semantic-release) - automates the whole package release workflow including: determining the next version number, generating the release notes and publishing the package.
* [standard-version](https://github.com/conventional-changelog/standard-version) - automate versioning and CHANGELOG generation, with [semver](https://semver.org/) and [conventional commit messages](https://conventionalcommits.org/).

### Boilerplate, scaffolding <a name="boilerplate"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Create React App](https://create-react-app.dev/) - create React apps with no build configuration.
* [create-react-library](https://github.com/transitive-bullshit/create-react-library) - CLI for easily creating reusable react libraries.
* [degit](https://github.com/Rich-Harris/degit) - straightforward project scaffolding. *degit* makes copies of git repositories.
* [fullstack-typescript](https://github.com/gilamran/fullstack-typescript) - FullStack React with TypeScript starter kit.
* [Neutrino](https://neutrinojs.org/) - a companion tool which lets you build web and Node.js applications with shared presets or configurations. It intends to make the process of initializing and building projects much simpler by providing minimal development dependencies.
* [nwb](https://github.com/insin/nwb) - a toolkit for React, Preact, Inferno & vanilla JS apps, React libraries and other npm modules for the web, with no configuration (until you need it).
* [React Starter Kit](https://reactstarter.com/) - an opinionated boilerplate for web development built on top of Node.js, Express, GraphQL and React, containing modern web development tools such as Webpack, Babel and Browsersync.
* [TSDX](https://github.com/jaredpalmer/tsdx) - a zero-config CLI that helps you develop, test, and publish modern TypeScript packages with ease.

### Component development <a name="component-dev"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [BlueKit](http://bluekit.blueberry.io/) - automatically generates a library from your React components with editable props and live preview.
* [component-playground](https://github.com/FormidableLabs/component-playground) - a component for rendering React Components and ES6 code with editable source and live preview.
* [Kit](https://github.com/c8r/kit) - tools for developing, documenting, and testing React component libraries.
* [Ladle](https://www.ladle.dev/) - develop and test your React stories faster. Ladle is a drop-in alternative to Storybook. It is a tool for developing and testing your React components in an environement that's isolated and faster than most real-world applications.
* [React Cosmos](https://github.com/react-cosmos/react-cosmos) - dev tool for creating reusable React components.
* [React Live](https://github.com/FormidableLabs/react-live) - brings you the ability to render React components and present the user with editable source code and live preview.
* [React Styleguidist](https://react-styleguidist.js.org/) - isolated React component development environment with a living style guide.
* [Storybook](https://storybook.js.org/) - a development environment for UI components. It allows you to browse a component library, view the different states of each component, and interactively develop and test components.

### Design <a name="design"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Playroom](https://github.com/seek-oss/playroom) - Simultaneously design across a variety of themes and screen sizes, powered by JSX and your own component library. Playroom allows you to create a zero-install code-oriented design environment, built into a standalone bundle that can be deployed alongside your existing design system documentation.

### Graphics/image editor <a name="image-editor"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [GIMP](https://www.gimp.org/) - a cross-platform image editor available for GNU/Linux, OS X, Windows and more operating systems.
* [Inkscape](https://inkscape.org/) - a free and open source vector graphics editor for GNU/Linux, Windows and MacOS X. It offers a rich set of features and is widely used for both artistic and technical illustrations such as cartoons, clip art, logos, typography, diagramming and flowcharting.
* [Krita](https://krita.org/) - a professional free and open source painting program. It is made by artists that want to see affordable art tools for everyone.
* [Paint.NET](https://www.getpaint.net/) - image and photo editing software for PCs that run Windows.

### Images, icons <a name="images"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [css.gg](https://css.gg/) - open-source CSS, SVG and Figma UI Icons, available in SVG Sprite, styled-components, NPM & API.
* [Eva Icons](https://akveo.github.io/eva-icons/) - a pack of more than 480 beautifully crafted Open Source icons for common actions and items. Icons are provided in two visual types: Fill and Outline and in several formats, including PNG, SVG, font, Sketch, etc.
* [Heroicons](https://heroicons.dev/) - a set of free MIT-licensed high-quality SVG icons for UI development.
* [icono](https://saeedalipoor.github.io/icono/) - pure css icons, with only one element.
* [Icons8](https://icons8.com/) - free icons, photos, vectors, music and tools.
* [IconSear.ch](https://iconsear.ch/search.html) - search engine for SVG icons.
* [Ikonate](https://www.ikonate.com/) - fully customisable & accessible, well-optimised vector icons.
* [Line Icons](https://lineicons.com/) - handcrafted line icons for modern user interfaces.
* [LogoSear.ch](https://logosear.ch/search.html) - search engine for SVG logos.
* [Lorem Picsum](https://picsum.photos/) - the Lorem Ipsum for photos. Easy to use, stylish image placeholders. Just add your desired image size (width & height) after our URL, and you'll get a random image.
* [Super Tiny Icons](https://github.com/edent/SuperTinyIcons) - miniscule SVG versions of your favourite website and app logos.
* [SVG Porn](https://svgporn.com/) - a huge collection of SVG logos.
* [Tabler Icons](https://tabler-icons.io/) - free and open source icons designed to make your website or app attractive, visually consistent and simply beautiful.
* [VectorLogoZone](https://www.vectorlogo.zone/) - consistently formatted SVG logos.

### Analysis, performance, optimization <a name="analysis"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Bundle Buddy](https://github.com/samccone/bundle-buddy) - a tool to help you find source code duplication across your javascript chunks/splits.
* [Bundle Phobia](https://bundlephobia.com/) - know the performance impact of including an npm package in your app's bundle.
* [Front-End Performance Checklist](https://github.com/thedaviddias/Front-End-Performance-Checklist) - an exhaustive list of elements you should check or at least be aware of, as a Front-End developer and apply to your project.
* [Lighthouse](https://developers.google.com/web/tools/lighthouse/) - an open-source, automated tool for improving the quality of web pages. It has audits for performance, accessibility, progressive web apps, and more.
* [Optimize your libraries with webpack](https://github.com/GoogleChromeLabs/webpack-libs-optimizations) - tips to make your webpack bundle smaller.
* [Package Phobia](https://packagephobia.com/) - reports the size of an npm package before you install it. This is useful for inspecting potential dependencies or devDependencies without using up precious disk space or waiting minutes for npm install.
* [Size Limit](https://github.com/ai/size-limit) - calculate the real cost of your JS for end users and throws an error if the cost exceeds the limit.
* [Source map explorer](https://github.com/danvk/source-map-explorer) - analyze and debug space usage through source maps. The source map explorer determines which file each byte in your minified code came from.
* [Waterfaller](https://waterfaller.dev/) - focuses on issues in the network waterfall and provides recommendations for improvement.
* [Webpack Bundle Analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) - webpack plugin and CLI utility that represents bundle content as convenient interactive zoomable treemap.
* [Webpack Visualizer](https://github.com/chrisbateman/webpack-visualizer) - visualize and analyze your Webpack bundle to see which modules are taking up space and which might be duplicates.
* [WebPagetest](https://www.webpagetest.org/) - run a free website speed test from multiple locations around the globe using real browsers and at real consumer connection speeds.
* [Yellow Lab Tools](https://yellowlab.tools/) - allows you to test a webpage (via an URL) and detects performance and front-end code quality issues.

### Network <a name="net"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [HTTPie](https://httpie.org/) - a command line HTTP client with an intuitive UI, JSON support, syntax highlighting, wget-like downloads, plugins, and more.
* [Insomnia](https://insomnia.rest/) - cross-platform HTTP and GraphQL Client.
* [LightProxy](https://lightproxy.org/) - cross platform web debugging proxy. LightProxy is a local proxy packet capture software.
* [Postwoman](https://postwoman.io/) - a free, fast and beautiful API request builder (web alternative to Postman).
* [Wireshark](https://www.wireshark.org/) - the world’s foremost and widely-used network protocol analyzer.

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
    - [http-server](https://github.com/http-party/http-server) - a simple, zero-configuration command-line http server.
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
    - [Laragon](https://laragon.org) - a portable, isolated, fast & powerful universal development environment for PHP, Node.js, Python, Java, Go, Ruby. It is fast, lightweight, easy-to-use and easy-to-extend.
    - [Uniform Server](http://www.uniformserver.com/) - a lightweight server solution for running a web server under the WindowsOS.
    - [UwAmp](http://www.uwamp.com/en/) - free Wamp Server with Apache MySQL PHP and SQLite.
    - [VertrigoServ](https://www.vswamp.com) - a complete free WAMP server allowing PHP development for Windows.
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
* [Leo](http://leoeditor.com/) - a PIM, IDE and outliner that accelerates the work flow of programmers, authors and web designers.
* [Light Table](http://lighttable.com/) - a next generation code editor that connects you to your creation with instant feedback. Light Table is very customizable and can display anything a Chromium browser can.
* [Notepad++](https://notepad-plus-plus.org/) - a free source code editor and Notepad replacement that supports several languages.
* [PSPad](https://www.pspad.com/) - text editor for developers for Microsoft Windows systems.
* [RJ TextEd](https://www.rj-texted.se/) - a full featured text and source editor with Unicode support. It is also a very powerful web (PHP, ASP, JavaScript, HTML and CSS) development editor.
* [Visual Studio Code](https://code.visualstudio.com/) - a new type of tool that combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. Code provides comprehensive editing and debugging support, an extensibility model, and lightweight integration with existing tools.

### Playground, interactive computing <a name="playground"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [nteract](https://nteract.io) - SDKs, applications, and libraries that help you and your team make the most of interactive notebooks and REPLs.
* [Quokka](https://quokkajs.com/) - a developer productivity tool for rapid JavaScript / TypeScript prototyping. Runtime values are updated and displayed in your IDE next to your code, as you type.
* [RunJS](https://runjs.app/) - a JavaScript playground that auto-evaluates your code as you type and outputs the results to a console pane.

### Online development/playground <a name="online-dev"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [CodeBunk](https://codebunk.com/) - the ultimate online coding interview tool. Collaborative Editor, compiler, chat.
* [CodeCollab](https://codecollab.io/) - an online real-time collaborative code editor and compiler. Our web-based application allows users to collaborate in real-time over the internet.
* [CodePen](https://codepen.io/) - a playground for the front end side of the web. It's a place to build and deploy a website, show off your work, build test cases, and find inspiration.
* [CodeSandbox](https://codesandbox.io/) - an online web application editor. Makes it easier to create, share and reuse web projects with others.
* [CodeShare](https://codeshare.io/) - an online code editor for interviews, troubleshooting, teaching & more.
* [ESNextbin](https://esnextb.in/) - create browser programs in ES2015 code and import modules from NPM in browser.
* [Flems.io](https://flems.io/) - a playground for web development. It's ideal for prototyping ideas & sharing working front-end code examples. Also see [Flems module](https://github.com/porsager/flems) which can be used for easy self hosting or embedding.
* [Glitch](https://glitch.com/) - the friendly community where everyone can discover and create the best stuff on the web.
* [JS Bin](https://jsbin.com/) - an open source collaborative web development debugging tool. Write code and have it both save in real-time, but also render a full preview in real-time.
* [jsFiddle](https://jsfiddle.net/) - an online playground for your JavaScript, HTML, CSS.
* [Repl.it](https://repl.it/) - simple, reliable, and portable cloud coding interface. A community of teachers, students and engineers.
* [RunKit](https://runkit.com/) - a node playground in your browser.
* [StackBlitz](https://stackblitz.com/) - the online code editor for web apps.

### Online tool <a name="online-tool"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [ExtendsClass](https://extendsclass.com/) - free online toolbox for developers. You have at your disposal syntax validators, code formatters, testers, HTTP clients, mock server, but also a SQLite browser.
* [Windframe](https://www.devwares.com/windframe/) - online visual builder for rapidly building and prototyping components and websites using tailwind css.

### Site generator <a name="site-generator"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [CMS.js](https://chrisdiana.dev/cms.js/) - fully client-side, Javascript site generator in the spirit of Jekyll that uses plain ol' HTML, CSS and Javascript to generate your website.
* [DocPad](https://github.com/docpad/docpad) - a dynamic static-site generator. That is a content management system that takes content from several sources, like files on your computer, and renders them into incredibly fast static output.
* [Elder.js](https://github.com/elderjs/elderjs) - an opinionated static site generator and web framework for Svelte built with SEO in mind.
* [Gatsby](https://www.gatsbyjs.com/) - blazing-fast static site generator for React.
* [Gridsome](https://gridsome.org/) - a Vue-powered static site generator for building CDN-ready websites for any headless CMS, local files or APIs.
* [Hexo](https://hexo.io/) - a fast, simple and powerful blog framework. You write posts in Markdown (or other languages) and Hexo generates static files with a beautiful theme in seconds.
* [Hugo](https://gohugo.io/) - a static HTML and CSS website generator written in Go. It is optimized for speed, ease of use, and configurability. Hugo takes a directory with content and templates and renders them into a full HTML website.
* [Lektor](https://www.getlektor.com/) - a flexible and powerful static content management system for building complex and beautiful websites out of flat files.

### Emulator, simulator <a name="emulator"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Responsinator](https://www.responsinator.com/) - helps website makers quickly get an indication of how their responsive site will look on the most popular devices.
* [Screenfly](http://quirktools.com/screenfly/) - allows you to view your website on a variety of device screens and resolutions.

### API <a name="api"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [APIs.guru](https://apis.guru/browse-apis/) - Wikipedia for WEB APIs.
* [ProgrammableWeb API directory](https://www.programmableweb.com/apis/directory) - directory where developers can search for APIs to include in their next software development project.
* [Public APIs](https://github.com/public-apis/public-apis) - a collective list of free APIs for use in software and web development.
* [public-apis.io](https://public-apis.io/) - a directory of free public & open Rest APIs.
* [RapidAPI](https://rapidapi.com/) - find and connect to thousands of APIs, track and manage all of your API connections in one place. RapidAPI lets you manage all your API integrations from one place and gives you real-time performance metrics.
* [Swagger](https://swagger.io/) - a powerful yet easy-to-use suite of API developer tools for teams and individuals, enabling development across the entire API lifecycle, from design and documentation, to test and deployment.

### Browser extension <a name="browser-extension"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* Chrome
  - [25 Essential Chrome Extensions for Web Designers](https://envato.com/blog/chrome-extensions-web-design/)
  - [Checkbot](https://www.checkbot.io/) - crawls your site testing pages follow 50+ SEO, speed and security best practices.
  - [CSS Peeper](https://csspeeper.com/) - smart CSS viewer tailored for designers.
  - [JS Bundle Size](https://github.com/vicrazumov/js-bundle-size) - automatically adds javascript bundle size data to npm and github project pages.
  - [Z-Context](https://github.com/gwwar/z-context) - displays stacking contexts and z-index values in the elements panel.

### Benchmark <a name="benchmark"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [CSS minification benchmark](http://goalsmashers.github.io/css-minification-benchmark/)
* [JS web frameworks benchmark](https://github.com/krausest/js-framework-benchmark) - a comparison of the perfomance of popular javascript frameworks.
* [UI Benchmark](https://localvoid.github.io/uibench/)

### Hosting, cloud services <a name="hosting"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [000webhost](https://www.000webhost.com/) & [hostinger.ru](https://www.hostinger.ru/) - zero cost website hosting with PHP, MySQL, Cpanel & no ads.
* [5apps Deploy](https://5apps.com/deploy/) - a turn-key deployment and hosting platform for client-side web apps.
* [Backendless](https://backendless.com/) - a leading mBaaS and powerful Mobile Application Development Platform that enables rapid development of feature-rich mobile, desktop and browser-based applications.
* [Cloudant](https://www.ibm.com/cloud/cloudant) - a highly scalable and performant JSON database.
* [Cloudnode](https://cloudno.de/) - a place to get your Javascript web applications up and running.
* [ExtendsClass](https://extendsclass.com/json-storage.html) - a simple JSON storage.
* [Firebase](https://firebase.google.com/) - a cloud-hosted database. Data is synchronized in realtime to every connected client.
* [HackMD](https://hackmd.io/) - best way to share knowledge in markdown.
* [Heroku](https://www.heroku.com/) - a cloud platform that lets companies build, deliver, monitor and scale apps.
* [JSONbin](https://jsonbin.io/) - a free JSON storage and JSON hosting service.
* [JSONSERVE](https://jsonserve.com/) - host your JSON easily and use in your apps.
* [Microsoft Azure](https://azure.microsoft.com/en-us/services/app-service/) - quickly create powerful cloud apps for web and mobile clients.
* [Netlify](https://www.netlify.com/) - builds, deploys, and hosts your front end.
* [now](https://zeit.co/now) - allows you to take your JavaScript (Node.js) or Docker powered websites, applications and services to the cloud with ease, speed and reliability.
* [Nuclino](https://www.nuclino.com/) - the easiest way to organize and share knowledge in teams. Create real-time collaborative documents and connect them instantly like a wiki. Use the tree, board, and graph view to explore and organize your knowledge visually. It's great for meeting notes, product requirements, docs, decisions, and more.
* [OpenShift](https://www.openshift.com/) - Red Hat's Platform-as-a-Service (PaaS) that allows developers to quickly develop, host, and scale applications in a cloud environment.
* [Pastebin](https://pastebin.com/) - a website where you can store any text online for easy sharing.
* [Rentry.co](https://rentry.co/) - a pastebin/publishing service with markdown support, preview, custom urls and editing. Fast, simple and free.
* [Surge](http://surge.sh/) - static web publishing for front-end developers.

### Code CDN <a name="code-cdn"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [ESM](https://esm.sh/) - a fast, global content delivery network for NPM packages with ES Module format.
* [jsDelivr](https://www.jsdelivr.com/) - a free, fast, and reliable Open Source CDN for npm & GitHub.
* [Skypack](https://www.skypack.dev/) - load optimized npm packages with no install and no build tools.
* [unpkg](https://unpkg.com/) - a fast, global content delivery network for everything on npm. Use it to quickly and easily load any file from any package.

### Guide, reference, practices, recipes <a name="guide"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [100+ Coding Interview Questions for Programmers](https://codeburst.io/100-coding-interview-questions-for-programmers-b1cf74885fb7) - solve these frequently asked coding problems to do well on your next programming job interviews.
* [30 seconds of code](https://www.30secondsofcode.org/) - short code snippets for all your development needs.
* [30 Seconds of Interviews](https://30secondsofinterviews.org/) - a curated collection of common interview questions to help you prepare for your next interview.
* [Checkbot: Web Best Practices](https://www.checkbot.io/guide/) - details 50+ SEO, speed and security web best practices.
* [DevDocs](https://devdocs.io/) - combines multiple API documentations in a fast, organized, and searchable interface.
* [Every Programmer Should Know](https://github.com/mtdvio/every-programmer-should-know) - a collection of (mostly) technical things every software developer should know.
* [Front End Interview Handbook](https://github.com/yangshun/front-end-interview-handbook) - almost complete answers to "Front-end Job Interview Questions" which you can use to interview potential candidates, test yourself or completely ignore.
* [Front-end Developer Interview Questions](https://h5bp.org/Front-end-Developer-Interview-Questions/) - a list of helpful front-end related questions you can use to interview potential candidates or test yourself.
* [Grab Front End Guide](https://github.com/grab/front-end-guide) - study guide and introduction to the modern front end stack.
* [OverAPI.com](https://overapi.com/) - collecting all cheat sheets.
* [Project Guidelines](https://github.com/elsewhencode/project-guidelines) - a list of guidelines that works really well with most JavaScript projects.
* [Service Worker Cookbook](https://serviceworke.rs/) - a collection of working, practical examples of using service workers in modern web sites.
* [Spellbook of Modern Web Dev](https://github.com/dexteryy/spellbook-of-modern-webdev) - a big picture, thesaurus, and taxonomy of modern JavaScript web development.
* [Tech Interview Handbook](https://yangshun.github.io/tech-interview-handbook/) - carefully curated content to help you ace your next technical interview, with a focus on algorithms.
* [Unix Toolbox](http://devdoc.net/linux/UnixToolbox.html) - a collection of Unix/Linux/BSD commands and tasks which are useful for IT work or for advanced users. This is a practical guide with concise explanations, however the reader is supposed to know what s/he is doing.
* CSS <a name="css-guide"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
    - [30 Seconds of CSS](https://www.30secondsofcode.org/css/) - a curated collection of useful CSS snippets you can understand in 30 seconds or less.
    - [A complete guide to CSS functions](https://css-tricks.com/complete-guide-to-css-functions/)
    - [Bootstrap Cheatsheet](https://bootstrap-cheatsheet.themeselection.com/) - an interactive list of Bootstrap classes, variables, and mixins.
    - [CSS Protips](https://github.com/AllThingsSmitty/css-protips) - a collection of tips to help take your CSS skills pro.
    - [CSS-Tricks](https://css-tricks.com/) - a site about all things web design and development.
    - [CSS Triggers](https://csstriggers.com/) - a reference for the render impact of mutating CSS properties.
    - [cssdb](https://cssdb.org/) - a comprehensive list of CSS features and their positions in the process of becoming implemented web standards.
    - [Modern CSS](https://moderncss.dev/) - modern CSS solutions for old CSS problems.
    - [Solved by Flexbox](https://philipwalton.github.io/solved-by-flexbox/) - a showcase of problems once hard or impossible to solve with CSS alone, now made trivially easy with Flexbox.
    - [The complete guide to CSS media queries](https://polypane.app/blog/the-complete-guide-to-css-media-queries/)
* HTML <a name="html-guide"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
    - [HTML Tips](https://markodenic.com/html-tips/) - some very useful HTML tips.
* JavaScript <a name="js-guide"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
    - [1loc](https://1loc.dev/) - favorite JavaScript utilities in single line of code.
    - [30 seconds of JavaScript](https://www.30secondsofcode.org/js/) - curated collection of useful JavaScript snippets that you can understand in 30 seconds or less.
    - [33 Concepts Every JavaScript Developer Should Know](https://github.com/leonardomso/33-js-concepts) - this repository was created with the intention of helping developers master their concepts in JavaScript. It is not a requirement, but a guide for future studies.
    - [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms) - JavaScript based examples of many popular algorithms and data structures.
    - [JavaScript Clean Code](https://github.com/ryanmcdermott/clean-code-javascript) - software engineering principles, from Robert C. Martin's book `Clean Code`, adapted for JavaScript.
    - [JavaScript Garden](http://bonsaiden.github.io/JavaScript-Garden/) - a growing collection of documentation about the most quirky parts of the JavaScript programming language.
    - [JavaScript Interview Questions & Answers](https://github.com/sudheerj/javascript-interview-questions) - list of 1000 JavaScript interview questions.
    - [JavaScript Questions](https://github.com/lydiahallie/javascript-questions) - a long list of (advanced) JavaScript questions, and their explanations. From basic to advanced: test how well you know JavaScript, refresh your knowledge a bit, or prepare for your coding interview!
    - [Modern JS Cheatsheet](https://mbeaudru.github.io/modern-js-cheatsheet/) - cheatsheet for the JavaScript knowledge you will frequently encounter in modern projects.
    - [Node.js Best Practices](https://github.com/goldbergyoni/nodebestpractices) - a summary and curation of the top-ranked content on Node JS best practices.
    - [The Modern JavaScript Tutorial](https://javascript.info)
    - [wtfjs](https://github.com/denysdovhan/wtfjs) - a list of funny and tricky JavaScript examples.
* TypeScript <a name="ts-guide"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
    - [TypeScript Cheatsheet](https://rmolinamir.github.io/typescript-cheatsheet/) - a set of TypeScript related notes used for quick reference. The cheatsheet contains references to types, classes, decorators, and many other TypeScript related subjects.
    - [TypeScript Cheatsheets](https://github.com/typescript-cheatsheets) - community curated cheatsheets for experienced JS developers to share knowledge and copy-paste recipes for common usecases.
    - [TypeScript Deep Dive](https://basarat.gitbook.io/typescript/) - the definitive guide to TypeScript.

### Books <a name="books"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Data Structures and Algorithms in JavaScript](https://github.com/amejiarosario/dsa.js-data-structures-and-algorithms-in-javascript) - data structures and algorithms explained and implemented in JavaScript.
* [Essential Image Optimization](https://images.guide/)
* [Freely available programming books](https://github.com/EbookFoundation/free-programming-books) - list of free learning resources.
* [Front-End Developer Handbook](https://frontendmasters.com/books/front-end-handbook/2019/) - a guide that anyone could use to learn about the practice of front-end development.
* [High Performance Browser Networking](https://hpbn.co/) - provides a hands-on overview of what every web developer needs to know about the various types of networks (WiFi, 3G/4G), transport protocols (UDP, TCP, and TLS), application protocols (HTTP/1.1, HTTP/2), and APIs available in the browser (XHR, WebSocket, WebRTC, and more) to deliver the best — fast, reliable, and resilient — user experience.
* [How to be a Programmer](https://www.gitbook.com/book/braydie/how-to-be-a-programmer/)
* [JavaScript Allongé](https://leanpub.com/javascriptallongesix/read) - a book about programming with functions.
* [Mostly adequate guide to functional programming](https://github.com/MostlyAdequate/mostly-adequate-guide) - a book on the functional paradigm in general (with JavaScript examples).
* [Patterns.dev](https://www.patterns.dev/) - free book on design patterns and component patterns for building powerful web apps with vanilla JavaScript and React.
* [React in patterns](https://legacy.gitbook.com/book/krasimir/react-in-patterns/details) - a book about common design patterns used while developing with React. It includes techniques for composition, data flow, dependency management and more.
* [SurviveJS](https://survivejs.com/) - books about React, Webpack and maintenance of JavaScript code.
* [The Complete JavaScript Handbook](https://www.freecodecamp.org/news/the-complete-javascript-handbook-f26b2c71719c/) - learn 80% of JavaScript in 20% of the time.
* [The JavaScript Way](https://github.com/thejsway/thejsway) - a gentle introduction to an essential language.

### Examples <a name="examples"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [Hacker News readers as Progressive Web Apps](https://hnpwa.com/) - a list of unofficial Hacker News clients built with a number of popular JavaScript frameworks and libraries. Each implementation is a complete Progressive Web App that utilizes different progressive technologies to provide a fast, reliable and engaging experience.
* [RealWorld](https://github.com/gothinkster/realworld) - see how the exact same Medium.com clone is built using any of our supported frontends and backends.
* [simpl.info](https://simpl.info/) - simplest possible examples of HTML, CSS and JavaScript.
* [TodoMVC](https://todomvc.com/) - helping you select an MV* framework.
* [Vanilla Web Projects](https://github.com/bradtraversy/vanillawebprojects) - mini projects built with HTML5, CSS & JavaScript. No frameworks or libraries.
* CSS <a name="css-examples"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
    - [CSS Arrows From CodePen](https://freebiesupply.com/blog/css-arrows/) - a list of CSS arrows from CodePen.
    - [CSS Background Patterns](https://www.magicpattern.design/tools/css-backgrounds) - beautiful pure CSS background patterns.
    - [CSS buttons](https://cssbuttons.io/) -  CSS buttons, checkboxes, and more. Choose from numerous UI components and get the CSS for the ones you like.
    - [CSSFX](https://cssfx.netlify.app/) - beautifully simple click-to-copy CSS effects. A carefully crafted collection designed with a focus on fluidity, simplicity, and ease of use. Powered by CSS with minimal markup.
    - [CSS Layout](https://csslayout.io/) - popular layouts & patterns made with CSS.
    - [Drop-in Minimal CSS](https://dohliam.github.io/dropin-minimal-css/) - an overview of barebones drop-in minimal CSS boilerplate frameworks.
    - [SpinKit](https://tobiasahlin.com/spinkit/) - a collection of loading indicators animated with CSS.
    - [The Shapes of CSS](https://css-tricks.com/the-shapes-of-css/) - lots of shapes in CSS with only a single HTML element.
    - [UI Snippets](https://ui-snippets.dev/) - a collection of UI Snippets.
* HTML <a name="html-examples"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
    - [HTML DOM](https://htmldom.dev/) - common tasks of managing HTML DOM with vanilla JavaScript.
    - [Sneat Free Bootstrap HTML Admin Template](https://github.com/themeselection/sneat-html-admin-template-free) - open-source & rasy to use Bootstrap 5 HTML admin template with elegant design & unique layout.

### Useful articles & resources <a name="resources"></a> [&#x2191;&nbsp;&#x2191;&nbsp;&#x2191;](#toc)
* [120+ Places To Find Creative Commons Media](https://www.sitepoint.com/creative-commons-sources/) - resources to search for audio, video, images and more for use in a project.
* [Awesome Algorithms](https://github.com/tayllan/awesome-algorithms) - a curated list of awesome places to learn and/or practice algorithms.
* [Keep a Changelog](https://keepachangelog.com/) - make it easier for users and contributors to see precisely what notable changes have been made between each release (or version) of the project.
* [Overview of the RenderingNG architecture](https://developer.chrome.com/blog/renderingng-architecture/) - overview of the Chrome RenderingNG architecture goals and key properties.
* [The cost of small modules](https://nolanlawson.com/2016/08/15/the-cost-of-small-modules/) (outdated) - demonstrates that small modules can have a surprisingly high performance cost depending on your choice of bundler and module system.
* [The cost of transpiling es2015 in 2016](https://github.com/samccone/The-cost-of-transpiling-es2015-in-2016) (outdated)
* [What Do the Popular JavaScript Tools Depend On?](https://www.telerik.com/blogs/popular-javascript-tools-depend) (outdated)
* [Why Performance Matters](https://developers.google.com/web/fundamentals/performance/why-performance-matters/)

[Table of contents &#x2191;](#toc)
