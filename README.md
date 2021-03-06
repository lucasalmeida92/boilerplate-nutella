Boilerplate Nutella
=====================

<p align="center">
  <img width="150" height="100" src="https://github.com/pedrobullo/boilerplate-nutella/blob/master/public/nutella.png">
</p>

<center>Cheio de modinha e açucar</center>

# Goal
Clean environment, Isomorphic (Universal) architecture ~~with lot sugar~~

# Razzle
Razzle is a tool that abstracts all complex configuration needed for SSR into a single dependency--giving you the awesome developer experience of create-react-app, but then leaving the rest of your app's architectural decisions about frameworks, routing, and data fetching up to you.
Pretty customizable (babelrc, lint, webpack.config).
Repo: [Razzle Lib](https://github.com/jaredpalmer/razzle/tree/master/packages/razzle)

# Sass and CSS Modules
```js
import style from 'my.scss'

<div className={style.mycontainer} />
```
TODO: Assets Critical path


# Usage
```
# Development
yarn install
yarn start
open http://localhost:3000

# Production
yarn install
yarn production
open http://localhost:5000

```

### ALTERNATIVE EXAMPLE
## Isomorphic Tools (Responsible to handle client/server exceptions, including assets). You can check at: [isomorphic-tools branch](https://github.com/pedrobj/boilerplate-nutella/tree/isomorphic-tools)

# Dependencies
* Webpack
* React + Redux
* [Razzle Universal Webpack Lib](https://github.com/jaredpalmer/razzle/tree/master/packages/razzle)
* [react-router](https://github.com/ReactTraining/react-router) - Declarative routing for React v4 :(. (TODO: Remove)
* [classnames](https://github.com/JedWatson/classnames) - A simple JavaScript utility for conditionally joining classNames together.
* [revalidator](https://github.com/flatiron/revalidator) - JSON schema validator
* [moment](https://github.com/moment/moment) - A lightweight JavaScript date library for parsing, validating, manipulating, and formatting dates.
* [sweetalert2](https://github.com/limonte/sweetalert2) - Replacement for JavaScript's popup boxes.
* [react-helmet](https://github.com/nfl/react-helmet) - A document head manager for React

# Plus
* Winston + exception logger

# Resources
* [react-router v4 stuff](https://reacttraining.com/react-router)
* [react-hot-boilerplate](https://github.com/gaearon/react-hot-boilerplate)
* [universal-react-redux-boilerplate](https://github.com/CrocoDillon/universal-react-redux-boilerplate)
* [isomorphic-boilerplate](https://github.com/mtmr0x/isomorphic-boilerplate)
* [atomic react](https://github.com/diegohaz/arc)
* [react-router guide](https://reacttraining.com/react-router/web/example/route-config)

# Patterns / LINT
* [ESLINT](https://github.com/eslint/eslint)

# TODOS:
* Styled component
* Better routing solution
* Code Splitting + Lazy Loading
* Assets critical path
