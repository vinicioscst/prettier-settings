# Prettier - Settings

> Personal setup for **Prettier** in VS Code.

## Extension

1. You'll need Prettier VS Code extension (`esbenp.prettier-vscode`).

## How to apply

1. After installing Prettier extension, use `CTRL + Shift + P` to open the command bar
2. Type `Preferences: Open User Settings (JSON)`
3. Add the following lines inside your JSON config:

```json
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true
```

4. In your project's root, add the `.prettierrc` file.
5. For any additional config, visit [**Prettier docs**](https://prettier.io/docs/en/)
