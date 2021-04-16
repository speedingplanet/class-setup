# Linting configuration

This is the linting configuration I use in class. It is a combination of changes to Visual Studio Code, ESLint, and Prettier. Coding style is important, of course. In class, there are some style choices which I think are helpful educationally which are not available through VS Code, ESLint, or Prettier alone. My general experience is that Prettier (or Standard!) is fine for code style outside of an educational or training context. ESLint is a very good linter. And VS Code is great for writing JavaScript and TypeScript. Thanks to the tools below, I wrestled the three of them into working together in a way that helps me. 

## Plugins

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) 
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) 
- [Format Code Action](https://marketplace.visualstudio.com/items?itemName=rohit-gohri.format-code-action): This is what makes everything work.

## Links

Most of the work in this area was done thanks to Rohit Gohri. 

- [Blog post](https://rohit.page/blog/posts/how-to-get-prettier-eslint-play-nicely-with-vscode) on getting ESLint and Prettier to work together
- [Original post](https://github.com/prettier/prettier-vscode/issues/1277#issuecomment-621175180), where the problem and solution are discussed
- Babel config thanks to this Stack Overflow answer: https://stackoverflow.com/a/66061810
- My [repo](https://github.com/johnpaxton/javascript-config) with the ESLint, Babel, and package lists

## Configuration

Install the plugins above. Below, you'll find the individual configurations for Visual Studio Code, Babel, Prettier, and ESLint

### Visual Studio Code
Add the following to your `settings.json` file in VS Code: 

```json
"[javascript]": {
  "editor.codeActionsOnSave": [
    "source.formatDocument",
    "source.fixAll.eslint"
  ],
  "editor.formatOnSave": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode"
},
```

### Babel
If you use any JavaScript features that are **not yet** ECMAScript standards, you will need Babel. Install the following:
  - @babel/preset-env
  - @babel/eslint-parser
  - @babel/eslint-plugin
  - @babel/plugin-syntax-class-properties

You will also need a .babelrc file. This one is in the .js format
```javascript
module.exports = function( api ) {
  api.cache( true );

  const presets = [ '@babel/env' ];
  const plugins = [ '@babel/plugin-syntax-class-properties' ];

  return {
    presets,
    plugins,
  };
};
```

### ESLint

```javascript
module.exports = {
  env: {
    browser: true,
    node: true,
    es2021: true,
  },

  // You don't need these if you're not using Babel
  plugins: [ '@babel' ],
  parser: '@babel/eslint-parser',

  extends: [ /* whatever */ ],
  rules: { /* whatever */ },
  ignorePatterns: [ 'node_modules' ],
};
```

### Prettier

Use the .prettierrc file format of your choice. Configure Prettier as usual.

