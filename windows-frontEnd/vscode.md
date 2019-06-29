# vscode 配置

## vscode 基础配置

- color theme 
- file icon theme
- end of line sequence `LF`

## 插件配置

- express
- GieLens
- prettier
- eslint
- Vetur

`/.vscode/settings.json` 配置

```json
{
    "files.eol": "\n",
    "files.autoSave": "off",
}
```

```json
// prettier

  "prettier.semi": true,
  "prettier.singleQuote": true,
  "editor.formatOnSave": true,

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





