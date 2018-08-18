## React app from scratch

Source: <https://blog.usejournal.com/creating-a-react-app-from-scratch-f3c693b84658>


### Steps

1. npm init & git init
2. mkdir public, mkdir src
3. add .gitignore (w node_modules & dist)
4. add /public/index.html
5. Babel:  run `npm install --save-dev babel-core@6.26.3 babel-cli@6.26.0 babel-preset-env@1.7.0 babel-preset-react@6.24.1`
6. add .babelrc
7. webpack: `npm install --save-dev webpack@4.12.0 webpack-cli@3.0.8 webpack-dev-server@3.1.4 style-loader@0.21.0 css-loader@0.28.11 babel-loader@7.1.4`
8. react: `npm i -s react@16.4.1 and react-dom@16.4.1`
9. add src/index.js & src/App.js
10. add App.css
11. add react-hot-loader `npm i -s react-hot-loader`
12. add react-hot-loader/babel to `.babelrc`

See repo at: <https://github.com/paradoxinversion/react-starter>
