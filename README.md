# eslint-typescript with react

https://blog.geographer.fr/eslint-guide

## vscode

"eslint.run": "onSave",

```
"eslint.validate": [
  "javascript",
  "javascriptreact",
  {
    "language": "typescript",
    "autoFix": true
  },
  {
    "language": "typescriptreact",
    "autoFix": true
  }
],
```

```
"javascript.preferences.quoteStyle": "single",
"typescript.preferences.quoteStyle": "single",
```

```
"javascript.updateImportsOnFileMove.enabled": "always",
"typescript.updateImportsOnFileMove.enabled": "always",
```