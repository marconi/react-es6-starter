# What is this?
There are many, many [great React starter kits](https://github.com/markerikson/react-redux-links/blob/master/boilerplates-and-starter-kits.md), but this one is **mine**. It includes the standard client-side libraries I would use on any new project: React, Moment, Lodash, npm, Babel (for ES6 support), Webpack, and ESLint. It also includes the ESLint rules I use for enforcing best practices when writing code using React/JSX, ES6, and Lodash. It also includes my standard Webpack config, which has auto-reloading, Babel transpilation, and CSS modules. It also uses `npm` as a build script (interfacing with webpack, etc.). To see a list of commands: `npm run`.

## Tooling

### ESLint

This repo uses [ESLint](http://eslint.org/), with rules defined in .eslintrc. It includes best practices for ES6, React, and Lodash. `npm run lint` will check code.

There many [IDE integrations for ESLint](http://eslint.org/docs/user-guide/integrations), but the recommended one for Sublime Text is [SublimeLinter](http://www.sublimelinter.com/en/latest/) with the [eslint plugin](https://github.com/roadhump/SublimeLinter-eslint).

### Babel

This repo uses Babel to convert ES6/ES2015 code to ES5, which can be run in all browsers. It's converted via Webpack, either on the fly with a dev server (`npm start`), or during a build step (`npm run build`).

Hint: [ES6 syntax highlighting in Sublime Text 3](https://github.com/babel/babel-sublime).

### Webpack

webpack.config.js is in a tooling folder. This is where karma.config.js would also go.
