# react-relay-graphql

- mkdir react-relay-graphql
- npm init
- npm install react@0.14.3
- npm install react-dom@0.14.3
- npm install babel-loader@6.2.0 babel-core@6.3.13 babel-preset-es2015@6.3.13 babel-preset-react@6.3.13 --save-dev
- npm install webpack -g
- Create index.html file and add a div with id="app" and a script tag src="public/bundle.js"
- Create a new file 'Main.js' under folder '/app/components'.
- Add react components to 'Main.js' file.
- Create a new file 'webpack.config.js'.
- In 'webpack.config.js' file, add exported module containing entry file, output file and module loaders.
- Run 'webpack -w'.
- npm install webpack-dev-server --save-dev
- Run "webpack-dev-server" (your app is running at http://localhost:8080/webpack-dev-server/)


- touch index.js
- npm install -g babel-cli
- npm install babel-preset-es2015 --save
- npm install graphql --save
- babel-node index.js --presets "es2015"
