drop-in template/toolchain for React + Bulma web app that supports modern JS code

get started with `npm i .`

to build in development, use `npx webpack --watch`

to build for production, use `npx webpack --mode production`

add your sass code to src/sass/styles.scss before `@import '../../node_modules/bulma/bulma.sass';`

add more babel plugins and presets to .babelrc (webpack will tell you if it needs more presets/plugins to pack the code you wrote)

this project uses `ky` if you need to do any http requests: https://github.com/sindresorhus/ky. it wraps the Fetch API, so you can use these options: https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/fetch

React, Sass, and Bulma are fun and easy! Check out the docs:

https://reactjs.org/docs/getting-started.html
https://sass-lang.com/guide
https://bulma.io/documentation/
