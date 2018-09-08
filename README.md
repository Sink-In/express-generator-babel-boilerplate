# Express Generator Babel Boilerplate
  * Added Babel support (ES6 and later) to the existing [express-generator](https://www.npmjs.com/package/express-generator)'s default directory without any changes in functionality.
  * Some additional configurations contains:
    * ESLint Airbnb
    * SASS
    * Twig
    
### Setup
  * `git clone https://github.com/sink-in/express-generator-babel-boilerplate.git`
  * `cd express-generator-boilerplate`
  * Remove `.git` directory.
  * `npm i` to install all the dependencies.
  * `npx install-peerdeps --dev eslint-config-airbnb` for ESLint Airbnb setup if not already installed on your system.
  
### Commands to Run
  * `npm start` or `npm run dev` for the development build with auto reload using [nodemon](https://www.npmjs.com/package/nodemon).
  * `npm run build` for production build. This will convert all the ES5+ code to ES5. After that you can run it from root directory via `node build/bin/index.js`.
  * `npm run clean` to remove the production directory.
  