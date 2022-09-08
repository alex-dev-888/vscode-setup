# VS CODE SETUP

## Extensions

| No  | Name                                          | Author             | Description                                                                           |
| --- | --------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------- |
| 1   | Auto Rename Tag                               | Jun Han            | Automatically rename paired HTML/XML tag                                              |
| 2   | Bracket Pair Colorizer                        | CoenraadS          | This extension allows matching brackets to be identified with colours                 |
| 3   | ES7 React/Redux/GraphQL/React-Native snippets | dsznajder          | JavaScript and React/Redux snippets in ES7+ with Babel plugin                         |
| 4   | indent-rainbow                                | oderwat            | A simple extension to make indentation more readable                                  |
| 5   | Live Server                                   | Ritwick Dey        | Launch a local development server with live reload feature for static & dynamic pages |
| 6   | MDX                                           | Matija Marohnić    | Adds language support for MDX                                                         |
| 7   | Prettier - Code formatter                     | Prettier           | Prettier is an opinionated code formatter                                             |
| 8   | Preview on Web Server                         | YuichiNukiyama     | Preview web page on Web Server                                                        |
| 9   | Svelte for VS Code                            | Svelte             | Provides syntax highlighting and rich intellisense for Svelte components in VS Code   |
| 10  | Svelte 3 Snippets                             | fivethree          | Adds Svelte 3 snippets to VS Code                                                     |
| 11  | Svelte Intellisense                           | ardenivanov        | Provides intellisense for data, events, slots etc. in components                      |
| 12  | vscode-styled-components                      | Julien Poissonnier | Syntax highlighting and IntelliSense for styled-components                            |
| 13  | DotENV                                        | mikestead          | VSCode .env syntax highlighting                                                       |
| 14  | Live Sass Compiler                            | Glenn Marks        | Compile Sass or Scss to CSS at realtime with live browser reload                      |
| 15  | React Native Tools                            | Microsoft          | Debugging and integrated commands for React Native                                    |
| 16  | React-Native/React/Redux snippets for es6/es7 | EQuimper           | Code snippets for React-Native/React/Redux es6/es7 and flowtype/typescript, Storybook                      |
| 17  | Material Icon Theme                           | Philipp Kief       | Material Design Icons for Visual Studio Code                                          |

## File Config

### Located to the following path:

1. MacOS: $HOME/Library/Application Support/Code/User/settings.json
2. $HOME/.config/Code/User/settings.json

```
{
  "editor.fontSize": 13,
  "files.autoSave": "off",
  "editor.wordWrap": "on",
  "terminal.integrated.fontSize": 11,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "editor.minimap.enabled": false,
  "prettier.jsxSingleQuote": true,
  "prettier.semi": false,
  "prettier.singleQuote": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.cursorBlinking": "expand",
  "window.zoomLevel": 2,
  "editor.tabSize": 2,
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "./dist"
    }
  ],
  "editor.fontFamily": "'Ubuntu Mono','Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'"
}
```
