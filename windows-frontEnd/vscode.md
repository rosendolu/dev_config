# vscode 配置

## vscode 基础配置

- color theme
  - One Dark Pro
- file icon theme
  - vscode-icons

## 插件配置

- Auto Import
- Bracket Pair Colorizer
- ESLint
- GitLens
- HTML Snippets
- IntelliSense For css class names in HTML
- minapp
- Node Require
- prettier
- eslint
- Vetur
- npm
- npm Intellisense
- One Dark Pro
- Path Intellisese
- Project Manager
- Remote WSL
- TODO Highlight

### Bracket Pair Colorizer

```json
// bracket pair colorizer
"bracketPairColorizer.highlightActiveScope": true,
"bracketPairColorizer.showBracketsInGutter": false,
// "bracketPairColorizer.showBracketsInRuler":true,
// "bracketPairColorizer.rulerPosition":"Right",
"bracketPairColorizer.scopeLineCSS": [
  "borderStyle : solid",
  "borderWidth : 2px",
  "borderColor : {color}; opacity: 1"
],
"bracketPairColorizer.activeScopeCSS": [
  "borderStyle : solid",
  "borderWidth : 1px",
  // "backgroundColor : {color}",
  "borderColor : {color}; opacity: 1"
],
"editor.matchBrackets": "never", // 关闭 vscode 默认匹配
```

`/.vscode/settings.json` 配置

```json
  "files.eol": "\n",
  "files.autoSave": "off"
```

```json
// prettier

  "prettier.semi": true,
  "prettier.singleQuote": true,
  "editor.formatOnSave": true,
  "prettier.endOfLine": "lf",
  "editor.defaultFormatter": "esbenp.prettier-vscode",

  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  }
```

```json
 // eslint
  "eslint.enable": true,
  "eslint.autoFixOnSave": true,
  "eslint.alwaysShowStatus": true,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    {
      "language": "vue",
      "autoFix": true
    }
  ],
```
