# Front-end technology list

The knowledge of learning articles is often fragmented. The front-end involves a wide range of aspects, and if this knowledge is not effectively combed, it cannot be connected in series to form a system. Therefore, I combined the work experience to abstract some of the front-end basic capabilities, and sorted out some good articles I have read and written to form a list of (pure) front-end technologies.

Whether you are self-learning front-end or familiar with some of the front-end technologies but some are not yet involved, I hope this list will help you review some of the front-end basic capabilities.

<!-- TOC -->

- [front-end technology list] (# front-end technology list)
    - [0. Annual Report] (#0-Annual Report)
    - [1. Foundation pick-up] (#1-Basic pick-up)
        - [1.1. JavaScript](#11-javascript)
        - [1.2. CSS](#12-css)
        - [1.3. Browser] (#13-browser)
    - [2. Engineering and Tools] (#2-Engineering and Tools)
        - [2.1. webpack](#21-webpack)
        - [2.2. Gulp](#22-gulp)
        - [2.3. Linter](#23-linter)
        - [2.4. Static Type (Typescript/Flow)] (#24-Static Typescriptflow)
        - [2.5. Babel](#25-babel)
        - [2.6. CSS Preprocessing and Modularization] (#26-css Preprocessing and Modularization)
    - [3. Performance Optimization] (#3-Performance Optimization)
        - [3.1. Load Performance] (#31 - Load Performance)
        - [3.2. Runtime Performance] (#32 - Runtime Performance)
        - [3.3. Front End Cache] (#33 - Front End Cache)
        - [3.4. Performance Tuning and Practice] (#34-Performance Debugging and Practice)
        - [3.5. Performance Indicators] (#35-Performance Indicators)
    - [4. Security] (#4-Security)
        - [4.1. XSS](#41-xss)
        - [4.2. CSRF](#42-csrf)
        - [4.3. CSP](#43-csp)
        - [4.4. HTTPS](#44-https)
        - [4.5. Security Record] (#45-Security Record)
    - [5. Automated Testing] (#5-Automated Testing)
        - [5.1. Unit Test] (#51-Unit Test)
        - [5.2. End-to-end test (E2E)] (#52-end-to-end test-e2e)
        - [5.3. Others] (#53-Others)
    - [6. Framework and Class Library] (#6-Frame and Class Library)
        - [6.1. React](#61-react)
        - [6.2. Vue](#62-vue)
        - [6.3. Redux](#63-redux)
        - [6.4. RxJS](#64-rxjs)
    - [7. New Technology / Directions] (#7 - New Technology Direction)
        - [7.1. PWA](#71-pwa)
        - [7.2. CSS Houdini](#72-css-houdini)
        - [7.3. Web Components](#73-web-components)
        - [7.4. Micro Frontends] (#74-Micro Frontends)
        - [7.5. HTTP/2](#75-http2)
        - [7.6. WebAssembly](#76-webassembly)
    - [8. Business related] (#8-business related)
        - [8.1. Data Routine Reporting] (#81-Data Rated Report)
        - [8.2. Front End Monitoring] (#82- Front End Monitoring)
        - [8.3. A/B test] (#83-ab test)
        - [8.4. "Server Push"] (#84-Server Push)
        - [8.5. Motion] (#85-dynamic)
    - [9. Good text not classified] (#9-good text not classified)

<!-- /TOC -->

## 0. Annual report

- [2018 Front End Tool Survey Report] (https://ashleynolan.co.uk/blog/frontend-tooling-survey-2018-results)
- [2018 JavaScript Survey Report] (https://2018.stateofjs.com/)

## 1. Basic pick up

> Knowing the new things when you are warm, you don’t know what you are learning, it is based on solid foundation.

### 1.1. JavaScript

- [You-Dont-Know-JS \[英\]] (https://github.com/getify/You-Dont-Know-JS)
- JavaScript basic operating mechanism:
    - [JS Engine, Runtime and Call Stack Overview\[英\]] (https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf)
    - [V8 Engine Introduction\[英\]] (https://blog.sessionstack.com/how-javascript-works-inside-the-v8-engine-5-tips-on-how-to-write-optimized- Code-ac089e62b12e)
    - [Memory Management and 4 Common Leaks [English]] (https://blog.sessionstack.com/how-javascript-works-memory-management-how-to-handle-4-common-memory-leaks -3f28b94cfbec)
- Event Loop (there will always be an Event Loop... in the interview):
    - [Exploring JavaScript Asynchrony and Browser Update Rendering Opportunities from the Event Loop Specification] (https://github.com/aooy/blog/issues/5)
    - [Asynchronous Event Loop \[英\]] (https://blog.sessionstack.com/how-javascript-works-event-loop-and-the-rise-of-async-programming-5-ways-to -better-coding-with-2f077c4438b5)
    - [Event Loop, Timers and `process.nextTick()` \[English\] in NodeJS (https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)
    - [Tasks, Microtasks, Queues and Schedules \[English\]] (https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/)
- [Web Workers and its 5 common usage scenarios\[英\]] (https://blog.sessionstack.com/how-javascript-works-the-building-blocks-of-web-workers-5-cases- When-you-should-use-them-a547c0757f6a)
- [How to avoid async/await hell\[英\]] (https://medium.freecodecamp.org/avoiding-the-async-await-hell-c77a0fb71c4c)
- ["Return to Hell" solution summary] (https://www.jianshu.com/p/bc7b8d542dcd)

### 1.2. CSS

- [You-Need-to-Know-CSS](https://lhammer.cn/You-need-to-know-css/#/)
- [CSS Layout Guide] (https://juejin.im/post/5b3b56a1e51d4519646204bb)
- [41⁄2 methods for implementing theme functions in (S)CSS\[英\]] (https://speakerdeck.com/csswizardry/4half-methods-for-theming-in-s-css)
- [Various line breaks in CSS\[英\]] (https://css-tricks.com/where-lines-break-is-complicated-heres-all-the-related-css-and-html /): Handling classic line breaks
- [What should I do if the browser has a precision error when converting rem to px? ](https://www.zhihu.com/question/264372456)
- [Precision-controlled scrolling experience, talk about the new standard Scroll Snap] (https://juejin.im/post/5ba079e86fb9a05d1227fddb)
- [How to perfectly implement a button for a non-button element\[英\]] (https://www.scottohara.me/blog/2018/10/03/unbutton-buttons.html)
- [Use CSS Grid to create horizontal scrolling container\[英\]] (https://uxdesign.cc/creating-horizontal-scrolling-containers-the-right-way-css-grid-c256f64fc585)
- [How to handle gaps in inline elements\[英\]] (https://css-tricks.com/fighting-the-space-between-inline-block-elements/)
- [The little-known pits in the CSS Stacking Context] (https://segmentfault.com/a/1190000002783265)

### 1.3. Browser

- [How the browser works] (https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)
- How does the modern browser work internally:
    - [Chrome Browser Overview] (https://developers.google.com/web/updates/2018/09/inside-browser-part1)
    - [What happened during browsing? ](https://developers.google.com/web/updates/2018/09/inside-browser-part2)
    - [The inner workings of the rendering process] (https://developers.google.com/web/updates/2018/09/inside-browser-part3)
    - [How does compositor improve interactive performance? ](https://developers.google.com/web/updates/2018/09/inside-browser-part4)
- [Complete page lifecycle API introduction\[英\]] (https://developers.google.com/web/updates/2018/07/page-lifecycle-api)
- [Four new observers: Intersection / Mutation / Resize / Performance (Observer)] (https://www.zeolearn.com/magazine/different-types-of-observers-supported-by-modern-browsers)
- [Rendering engine working mode and optimization suggestions\[英\]] (https://blog.sessionstack.com/how-javascript-works-the-rendering-engine-and-tips-to-optimize-its-performance- 7b95553baeda)
- [Browser Kernel Rendering: Rebuild Engine] (https://juejin.im/post/5bbaa7da6fb9a05d3761aafe)
- [Cross-domain solution summary] (https://www.jianshu.com/p/438183ddcea8)

## 2. Engineering and tools

> The expansion of software scale has brought about engineering needs, and the front end is no exception. With the advent of NodeJS, front-end engineers can use the familiar JS to quickly develop the tools they need. The prosperity of the tool chain ecology is also a portrayal of the prosperity of the front-end circle.

### 2.1. webpack

- [Chunk diagram algorithm in webpack\[英\]] (https://medium.com/webpack/the-chunk-graph-algorithm-week-26-29-7c88aa5e4b4e)
- [webpack advanced series article] (https://juejin.im/post/5bc1a73df265da0a8d36b74f#heading-13)
- Compile optimization:
    - [How to improve the performance of webpack in large projects 🎥 \[英\]] (https://www.youtube.com/watch?v=AifDI71uqF0)
    - [Runtime optimization: Separating a Manifest \[英\]] (https://survivejs.com/webpack/optimizing/separating-manifest)
    - [Use \<link rel=”prefetch/preload” in webpack> \[英\]] (https://medium.com/webpack/link-rel-prefetch-preload-in-webpack-51a52358f84c)
    - [How to better use webpack tree-shaking] (https://juejin.im/post/5b8ce49df265da438151b468)
- Discussion on webpack compilation cache:
    - [mzgoddard's comment](https://github.com/webpack/webpack/issues/250#issuecomment-240643985)
    - [\[spec: webpack 5\] - A module disk cache between build processes] (https://github.com/webpack/webpack/issues/6527)

### 2.2. Gulp

- [Gulp 4 Introduction\[英\]] (https://fettblog.eu/gulp-4-parallel-and-series/)
- [Gulp-based multi-page application practice guide] (https://www.jianshu.com/p/35571124770f)

### 2.3. Linter

- [JS Linter Evolutionary History] (https://zhuanlan.zhihu.com/p/34656263)
- [Why use ESLint \[英\] in the project summary (https://medium.com/the-node-js-collection/why-and-how-to-use-eslint-in-your-project- 742d0bc61ed7)

### 2.4. Static Type (Typescript/Flow)

- [Typescript Overall Architecture\[英\]] (https://github.com/Microsoft/TypeScript/wiki/Architectural-Overview)
- Why do static type checking in JavaScript:
    - [Part 1] (https://www.jianshu.com/p/bda750e2d15e)
    - [Part 2, 3] (https://www.jianshu.com/p/289b3c734a9f)
    - [Part 4] (https://www.jianshu.com/p/d23f93be8821)

### 2.5. Babel

- [Babel User Manual] (https://github.com/jamiebuilds/babel-handbook/blob/master/translations/zh-Hans/user-handbook.md)
- [Babel Plugin Handbook] (https://github.com/jamiebuilds/babel-handbook/blob/master/translations/zh-Hans/plugin-handbook.md)

### 2.6. CSS Preprocessing and Modularization

- [CSS Evolutionary History\[英\]] (https://medium.com/@perezpriego7/css-evolution-from-css-sass-bem-css-modules-to-styled-components-d4c1da3a659b)
- [CSS Modular Solution Series] (https://juejin.im/post/5b20e8e0e51d4506c60e47f5)

## 3. Performance Optimization

> Performance optimization is actually based on the understanding of the browser, "adapted to local conditions", so it can be understood in conjunction with Section 1.3 "Browser".

It’s highly recommended to read through the articles in the [Performance Optimization on Google Web] (https://developers.google.com/web/fundamentals/performance/why-performance-matters/) Tab, which is basically covered in modern browsers. All points of performance optimization, very systematic. The following is also an excerpt from some of the personally considered very good lengths.

### 3.1. Loading performance

- [PRPL mode\[英\]] (https://developers.google.com/web/fundamentals/performance/prpl-pattern/)
- [Picture lazy loading full guide\[英\]] (https://css-tricks.com/the-complete-guide-to-lazy-loading-images)
- [Use Intersection Observer to lazy to load images\[英\]] (http://deanhume.com/lazy-loading-images-using-intersection-observer/)
- [Detailed Guide to Image and Video Lazy Loading\[英\]] (https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
- [Using the Application Shell architecture to implement the second open application\[英\]] (https://developers.google.com/web/updates/2015/11/app-shell)

### 3.2. Runtime performance

- [Avoid large, complex layouts and layout jitters\[英\]] (https://developers.google.com/web/fundamentals/performance/rendering/avoid-large-complex-layouts-and-layout-thrashing? Hl=zh-cn#avoid-forced-synchronous-layouts)
- [What causes a forced synchronization layout (reflow)? \[英\]](https://gist.github.com/paulirish/5d52fb081b3570c81e3a)
- [How to diagnose forced sync layout\[英\]] (https://developers.google.com/web/tools/chrome-devtools/rendering-tools/forced-synchronous-layouts?hl=en)
- [Wireless Performance Optimization: Composite] (http://taobaofed.org/blog/2016/04/25/performance-composite/)
- [How to improve the performance of the scroll event by any means] (https://zhuanlan.zhihu.com/p/30078937)
- [Use passive event listener to improve scrolling fluency\[英\]] (https://github.com/WICG/EventListenerOptions/blob/gh-pages/explainer.md)
- Throttling & debounce:
    - [JavaScript function throttling and function debounce application scenario analysis] (https://github.com/hanzichi/underscore-analysis/issues/20)
    - [Unscore function debounce implementation] (https://github.com/hanzichi/underscore-analysis/issues/21)
- requestIdleCallback - a powerful and artifact-like API:
    - [requestIdleCallback Getting Started\[英\]] (https://developers.google.com/web/updates/2015/08/using-requestidlecallback)
    - [Idle Until Urgent \[英\]](https://philipwalton.com/articles/idle-until-urgent): the magic of requestIdleCallback

### 3.3. Front-end caching

- [Introduction to Web Cache: Take the purchase of milk as an example\[英\]] (https://dev.to/kbk0125/web-caching-explained-by-buying-milk-at-the-supermarket-9k4)
- [Large Front End Cache\[英\]] (https://calendar.perfplanet.com/2016/a-tale-of-four-caches/)
- [Cache (1) - Cache Overview: Cache from a performance optimization perspective] (https://github.com/amandakelake/blog/issues/43)
- [Cache (2) - Browser caching mechanism: strong cache, negotiated cache] (https://github.com/amandakelake/blog/issues/41)
- [Cache (3) - Data Storage: Cookie, Storage, IndexedDB] (https://github.com/amandakelake/blog/issues/13)

### 3.4. Performance debugging and practice

- [Use Chrome DevTools to increase page speed\[英\]] (https://developers.google.com/web/tools/chrome-devtools/speed/get-started): Chrome DevTools
- [Understanding Resource Timing in DevTools] (https://developers.google.com/web/tools/chrome-devtools/network-performance/understanding-resource-timing)
- [Taobao New Force Week H5 Performance Optimization Practice] (https://segmentfault.com/a/1190000014359615)
- [Optimize packaging strategy to improve page load speed] (https://juejin.im/post/5aed037b6fb9a07aa047e1e1)
- [Debugging tips you may not know in Chrome DevTools] (https://zhuanlan.zhihu.com/p/42059158)
- [front-end performance measurement\[英\]] (https://speedcurve.com/blog/user-timing-and-custom-metrics/)

### 3.5. Performance Indicators

- [User-centric front-end performance metrics\[英\]] (https://developers.google.com/web/fundamentals/performance/user-centric-performance-metrics): The ins and outs of front-end performance metrics
- DOMContentLoaded:
    - [DOMContentLoaded you don't know] (https://zhuanlan.zhihu.com/p/25876048)
    - [Deciphering the Critical Rendering Path \[英\]] (https://calendar.perfplanet.com/2012/deciphering-the-critical-rendering-path/)
- FP (First Paint):
    - [Chrome's First Paint] (http://eux.baidu.com/blog/fe/Chrome%E7%9A%84First%20Paint)
- FCP (First Contentful Paint):
    - [First Contentful Paint Explained \[英\]](https://gtmetrix.com/blog/first-contentful-paint-explained/)
    - [First Contentful Paint \[英\]] (https://developers.google.com/web/tools/lighthouse/audits/first-contentful-paint)
- FMP (First Meaningful Paint):
    - [First Meaningful Paint in Chrome] (https://juejin.im/entry/598080226fb9a03c5d535cd5)
    - [Time to First Meaningful Paint] (https://docs.google.com/document/d/1BR94tJdZLsin5poeet0XoTW60M0SjvOJQttKT-JK8HI/view?hl=zh-cn#heading=h.k50nnyhtptq0)
- TTI (Time to interactive):
    - [Time to Interactive Explainer] (https://github.com/WICG/time-to-interactive)
    - [A new standard for measuring user experience] (https://calendar.perfplanet.com/2017/time-to-interactive-measuring-more-of-the-user-experience/)
- TTFB (Time To First Byte):
    - [TTFB, and the time node for page loading] (https://zhuanlan.zhihu.com/p/23588780)
- FID (First Input Delay):
    - [First Input Delay] (https://developers.google.com/web/updates/2018/05/first-input-delay)
- Speed ​​Index:
    - [WebPagetest: Speed ​​Index] (https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index)

## 4. Security

> Many security risks are commonplace, but they are often valued or recognized when problems arise.

- [8 Top Front End Security Issues] (https://insights.thoughtworks.cn/eight-security-problems-in-front-end/)
- [8 major front-end security issues] (http://insights.thoughtworks.cn/eight-security-problems-in-front-end-2/)
- [Conceptual explanation: coding, encryption, hashing and confusion\[英\]] (https://danielmiessler.com/study/encoding-encryption-hashing-obfuscation)
- [Common Web Security Attack and Defense Summary] (https://zoumiaojiang.com/article/common-web-security/)

### 4.1. XSS

- [How to prevent XSS attacks? ](https://tech.meituan.com/fe_security.html)

### 4.2. CSRF

- [How to prevent CSRF attacks? ](https://juejin.im/post/5bc009996fb9a05d0a055192)
- [Site Isolation \[英\]] (https://developers.google.com/web/updates/2018/07/site-isolation): What's new in Chrome

### 4.3. CSP

- [Content Security Policy Getting Started Tutorial] (http://www.ruanyifeng.com/blog/2016/09/csp.html)
- [Content Security Policy (CSP) \[English\]] (https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP)

### 4.4. HTTPS

- [Image Restoration HTTPS Principle] (https://mp.weixin.qq.com/s/3NKOCOeIUF2SGJnY7II9hA)
- [Talk about the full station HTTPS advancement] (https://segmentfault.com/a/1190000013635363)

### 4.5. Security Record

- [About `rel=noopener` \[英\]](https://mathiasbynens.github.io/rel-noopener/): How to open a new page is a security risk
- [A new type of "fishing" method \[英\]] (http://www.azarask.in/blog/post/a-new-type-of-phishing-attack/)
- [Cross-site risk caused by a media file request\[英\]] (https://jakearchibald.com/2018/i-discovered-a-browser-bug)
- [Mitigating Spectre \[英\]] (https://security.googleblog.com/2018/07/mitigating-spectre-with-site-isolation.html): Cross-site security issues in Chrome

## 5. Automated testing

> Automated testing is an important part of software engineering, but it is extremely easy to ignore.

- [2018 Front End Automation Test Overview\[英\]] (https://medium.com/welldone-software/an-overview-of-javascript-testing-in-2018-f68950900bc3)
- [Test your front-end code (introduction)\[英\]] (https://hackernoon.com/testing-your-frontend-code-part-i-introduction-7e307eac4446)

### 5.1. Unit testing

- [Test your front-end code (unit test articles)\[英\]] (https://hackernoon.com/testing-your-frontend-code-part-ii-unit-testing-1d05f8d50859)
- [Fakes, Mocks, and Stubs concepts are clear] (https://zhuanlan.zhihu.com/p/26942686)
- [What is the use of test coverage (rate)? ](http://www.infoq.com/cn/articles/test-coverage-rate-role)

### 5.2. End-to-end testing (E2E)

- [Test your front-end code (E2E test article)\[英\]] (https://hackernoon.com/testing-your-frontend-code-part-iii-e2e-testing-e9261b56475)
- [What is a good E2E test? \[英\]](https://testing.googleblog.com/2016/09/testing-on-toilet-what-makes-good-end.html)
- [Balance unit testing and end-to-end testing] (http://www.infoq.com/cn/articles/balancing-unit-and-end-to-end-tests)
- [say "no" for too many E2E tests \[英\]] (https://testing.googleblog.com/2015/04/just-say-no-to-more-end-to-end-tests .html)

### 5.3. Others

- [Test your front-end code (integration test)\[英\]] (https://hackernoon.com/testing-your-frontend-code-part-iv-integration-testing-f1f4609dc4d9)
- [Test your front-end code (visualization test)\[英\]] (https://medium.com/@giltayar/testing-your-frontend-code-part-v-visual-testing-935864cfb5c7)

## 6. Framework and class library

> If the basics are the Tao, then the framework and tools may be surgery; learn and understand them, but don't be slaves to them.

### 6.1. React

- [React bottom secret \[英\]] (https://bogdan-lyashenko.github.io/Under-the-hood-ReactJS/)
- [React details you need to know] (https://github.com/hateonion/react-bits-CN)
- [React Fiber Architecture] (https://zhuanlan.zhihu.com/p/37095662)
- [React 16 Fiber Quick Start] (http://zxc0328.github.io/2017/09/28/react-16-source/)
- [How React is made] (https://segmentfault.com/a/1190000013365426): React's early evolutionary path
- Implement a React from scratch:
    - [1. JSX and Virtual DOM] (https://github.com/hujiulong/blog/issues/4)
    - [2. Components and Lifecycle] (https://github.com/hujiulong/blog/issues/5)
    - [3. diff algorithm] (https://github.com/hujiulong/blog/issues/6)
    - [4. Asynchronous setState] (https://github.com/hujiulong/blog/issues/7)
- ["react technology stack" single page application practice quick start] (https://www.jianshu.com/p/0b2acb50f321)

### 6.2. Vue

- [Introduction - vue change detection principle] (https://github.com/berwin/Blog/issues/17)
- [Vue template compilation principle] (https://github.com/berwin/Blog/issues/18)

### 6.3. Redux

- [Redesign Redux \[英\]] (https://hackernoon.com/redesigning-redux-b2baee8b8a38): Rematch
- [How to replace Redux with [GraphQL] [https://hackernoon.com/how-graphql-replaces-redux-3fff8289221d)
- [Interpreting Redux's design ideas and usage] (https://div.io/topic/1309)
- [(Redux) application builds three principles\[英\]] (https://jaysoo.ca/2016/02/28/organizing-redux-application/#rule-1-organize-by-feature)

### 6.4. RxJS

- [ReactiveX official website] (http://reactivex.io/): The gem map is really very easy to read.
- [Responsive programming, is a wise choice] (https://www.cnblogs.com/android-blogs/p/5586395.html)
- [Illustration RxJS \[英\]] (https://blog.angularindepth.com/learn-to-combine-rxjs-sequences-with-super-intuitive-interactive-diagrams-20fce8e6511)
- [Debug RxJS: Tooling \[英\]] (https://blog.angularindepth.com/debugging-rxjs-4f0340286dd3)
- [Debug RxJS: Logging \[英\]] (https://blog.angularindepth.com/debugging-rxjs-part-2-logging-56904459f144)


## 7. New Technology / Direction

> New technologies and new directions in the front-end field are emerging one after another. Here are some new technology directions; as developers need to know more but don't blindly follow

### 7.1. PWA

- [PWA Learning and Practice Series] (https://juejin.im/post/5ac8a67c5188255c5668b0b8#heading-3)
- [Introduction to Service Worker\[英\]] (https://medium.freecodecamp.org/service-workers-the-little-heroes-behind-progressive-web-apps-431cc22d0f16)
- [PWA special issue on iOS\[英\]] (https://medium.com/@firt/pwas-are-coming-to-ios-11-3-cupertino-we-have-a- Problem-2ff49fd7d6ea)
- [Use the iOS meta tag \[英\] in your PWA (https://medium.com/@firt/dont-use-ios-web-app-meta-tag-irresponsibly-in-your -progressive-web-apps-85d70f4438cb)
- [Hungry PWA upgrade practice] (https://medium.com/elemefe/upgrading-ele-me-to-progressive-web-app-2a446832e509)
- [Offline Guide] (https://developers.google.com/web/fundamentals/instant-and-offline/offline-cookbook/)
- [WebAPKs in Android \[英\]] (https://developers.google.com/web/fundamentals/integration/webapks?hl=en)
- [Pinterest's PWA Practice\[英\]] (https://medium.com/@Pinterest_Engineering/a-one-year-pwa-retrospective-f4a2f4129e05)
- [Asynchronous HTTP Cookies API \[英\]] (https://developers.google.com/web/updates/2018/09/asynchronous-access-to-http-cookies): Empowering Service Worker

### 7.2. CSS Houdini

- [Know Houdini and CSS Paint API \[英\]] (https://codersblock.com/blog/say-hello-to-houdini-and-the-css-paint-api/)
- [Use Houdini to save CSS Polyfill \[英\]] (https://philipwalton.com/articles/the-dark-side-of-polyfilling-css/)

### 7.3. Web Components

- [Web Components Basic Concepts and Usage] (https://developer.mozilla.org/en-us/docs/Web/Web_Components)
- [Web Components Guide\[英\]] (https://css-tricks.com/modular-future-web-components/)
- [Shadow DOM Usage Profile] (http://web.jobbole.com/87088/)
- [HTMLUnknownElement and HTML5 custom element story] (http://www.zhangxinxu.com/wordpress/2018/03/htmlunknownelement-html5-custom-elements/)

### 7.4. Micro Frontends

- [Micro Front End Home\[英\]] (https://micro-frontends.org/)
- [Those things about the micro front end] (https://microfrontend.cn/)
- [Technical Radar's "Micro Front End" - Extending the Microservices Concept to Front End Development] (https://zhuanlan.zhihu.com/p/32378432)

### 7.5. HTTP/2

- [HTTP/2 behind-the-scenes principle] (https://www.ibm.com/developerworks/cn/web/wa-http2-under-the-hood/index.html)
- [Comprehensive introduction of HTTP/2 \[英\]] (https://hpbn.co/http2/)
- [HTTP/2 home page] (https://http2.github.io/):
    - [HTTP/2 Protocol\[英\]] (https://httpwg.org/specs/rfc7540.html)
    - [HPACK: HTTP/2 Header Compression\[英\]] (https://httpwg.org/specs/rfc7541.html)

### 7.6. WebAssembly

- [WebAssembly official website] (https://webassembly.org/)
- [WebAssembly Status and Actual Combat] (https://www.ibm.com/developerworks/cn/web/wa-lo-webassembly-status-and-reality/index.html)
- WebAssembly series:
    - [I. Introducing WebAssembly vividly] (https://segmentfault.com/a/1190000008714589)
    - [2. JavaScript Just-in-time (JIT) How it works] (https://segmentfault.com/a/1190000008632441)
    - [three, how the compiler generates assembly] (https://segmentfault.com/a/1190000008664761)
    - [four, WebAssembly working principle] (https://segmentfault.com/a/1190000008686643)
    - [V. Why is WebAssembly faster? ](https://segmentfault.com/a/1190000008699213)
    - [Six, WebAssembly's present and future] (https://segmentfault.com/a/1190000008714515)

## 8. Business related

> There are often some “business-independent” scenarios in the business – no matter what the business is almost always encountered; therefore, in the change and the constant, we need to abstract these issues.

### 8.1. Data management

- [How to accurately count the duration of the page] (https://techblog.toutiao.com/2018/06/05/ru-he-jing-que-tong-ji-ye-mian-ting-liu-shi-chang/ )
- [Unveil the mystery of JS non-buried technology] (http://unclechen.github.io/2018/06/24/%E6%8F%AD%E5%BC%80JS%E6%97%A0%E5 %9F%8B%E7%82%B9%E6%8A%80%E6%9C%AF%E7%9A%84%E7%A5%9E%E7%A7%98%E9%9D%A2%E7%BA %B1/)

### 8.2. Front-end monitoring

- [Lead-end anomaly monitoring solution research] (https://cdc.tencent.com/2018/09/13/frontend-exception-monitor-research/)
- [Monitoring platform front-end SDK development practices] (https://tech.meituan.com/hunt_sdk_practice.html)
- [Take the front-end monitoring to the extreme] (https://zhuanlan.zhihu.com/p/32262716)
- [Front-end monitoring system exploration summary] (https://juejin.im/post/5a3e121451882533f01ec66d)

### 8.3. A/B test

- Twitter A/B testing practice:
    - [1. Why test and test the meaning] (http://www.infoq.com/cn/articles/twitter-ab-test-practise-part01)
    - [II. Technical Overview] (http://www.infoq.com/cn/articles/twitter-ab-test-practise-part02)
    - [3. Detecting and avoiding bucket imbalance in A/B Test] (http://www.infoq.com/cn/articles/twitter-ab-test-practise-part03)
    - [4. Inspiration for using multiple controls in A/B Test] (http://www.infoq.com/cn/articles/twitter-ab-test-practise-part04)
- [Netflix A/B Test Labs Practice\[英\]] (https://medium.com/netflix-techblog/its-all-a-bout-testing-the-netflix-experimentation-platform-4e1ca458c15)
- Guidance method
    - [Seven questions that are easy to encounter in the experiment\[英\]] (https://www.exp-platform.com/Documents/2009-ExPpitfalls.pdf)
    - [Seven Guidelines for Experiments\[英\]] (https://www.exp-platform.com/Documents/2014%20experimentersRulesOfThumb.pdf)
    - [How to conduct AB test for small traffic] (https://www.jianshu.com/p/3ab537f16b81)
- Case Studies
    - [Popular Review AB Test Framework Gemini] (https://www.csdn.net/article/2015-03-24/2824303)
    - [Sina News Client AB Test and Grayscale Release] (https://segmentfault.com/a/1190000012377139)
    - [Tmall App A/B Testing Practice] (http://www.infoq.com/cn/articles/tmall-app-ab-test)
- Tools
    - [AB Test Sample Quantity Calculator] (https://www.eyeofcloud.com/124.html)
    - [AB Test Results Validation Analysis Tool] (https://www.eyeofcloud.com/126.html)

### 8.4. "Server push"

- [All kinds of "server push" technology principles and examples] (https://juejin.im/post/5b135b78f265da6e420eab7d)
- [Long connection / websocket / SSE and other mainstream server push technology comparison] (https://zhuanlan.zhihu.com/p/31297574)
- [Comet: "Server Push" Technology Based on HTTP Long Connection] (https://www.ibm.com/developerworks/cn/web/wa-lo-comet/)
- [Deep WebSockets, HTTP/2 SSE \[英\]] (https://blog.sessionstack.com/how-javascript-works-deep-dive-into-websockets-and-http-2-with-sse- How-to-pick-the-right-path-584e6b8e3bf7)
- [WebSocket Application Security Analysis] (https://security.tencent.com/index.php/blog/msg/119)

### 8.5. Dynamic effects

- [12 principles of animation design 🎥 \[英\]] (https://www.youtube.com/watch?v=uDqjIdI4bF4)
- [Bessel Curve Literacy] (http://www.html-js.com/article/1628)
- [Animation: From AE to Web] (https://aotu.io/notes/2018/03/06/ae2web/)
- The most complete and most effective method of landing:
    - [Basic knowledge] (https://zhuanlan.zhihu.com/p/34501702)
    - [Floor mode] (https://zhuanlan.zhihu.com/p/34815524)

## 9. Good text not classified

> Open roll is beneficial.

- [Recursion? We don't need no stinking recursion!] (http://raganwald.com/2018/05/20/we-dont-need-no-stinking-recursion.html): How to change some recursion Loop (tail recursion optimization)
- [Turning your web traffic into a Super Computer] (https://ben.akrin.com/?p=5997): Connect computers around the world into supercomputers via Web Worker and WebSocket
- [Designing very large (JavaScript) applications] (https://medium.com/@cramforce/designing-very-large-javascript-applications-6e013a3291a3): High-rise building, suitable for reading and thinking
