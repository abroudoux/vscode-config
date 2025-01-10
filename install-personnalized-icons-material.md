Go to `/Users/your_username/.vscode/extensions/pkief.material-icon-theme-{material_icons_version}/icons` and upload the svg of your choice.

```bash
mv ~/Downloads/gleam.svg /Users/your_username/.vscode/extensions/pkief.material-icon-theme-{material_icons_version}/icons/
```

Open `User Settings (JSON)` and paste these lines to configure the new icons:

```json
"material-icon-theme.files.associations": {
    // change icon of .gleam files
    "*.gleam": "gleam",
  }
```
