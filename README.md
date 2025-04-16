# berkeley-theme

![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/ocat.berkeley-theme?color=0a805d)

Inspired by https://usgraphics.com/

## Marketplace

https://marketplace.visualstudio.com/items?itemName=ocat.berkeley-theme

## Screenshots

![Screenshot1](./images/screenshot/preference1.png)
![Screenshot2](./images/screenshot/preference2.png)

## Recommend Font

https://usgraphics.com/products/berkeley-mono

settings.json

```json
...
"editor.fontFamily": "Berkeley Mono",
"terminal.integrated.fontFamily": "Berkeley Mono, Hack Nerd Font",
...
```

## Contributing

Contributions are welcome.

admin dashboard
https://marketplace.visualstudio.com/manage/publishers/ocat

## Publish

```bash
commit...

vsce publish patch
vsce publish minor
vsce publish major
```

## Change Explorer Font to Berkeley Mono)

- Custom CSS and JS for Visual Studio Code
  - https://marketplace.visualstudio.com/items/?itemName=be5invis.vscode-custom-css

`~/.vscode/tree.css`

```css
.sidebar .explorer-viewlet .label-name,
.editor .title .label-name {
  font-family: "Berkeley Mono" !important;
  font-size: 12px !important;
}

.split-view-view {
  font-family: "Berkeley Mono" !important;
  font-size: 12px !important;
}
```

Command + Shift + P

```text
> Enable Custom CSS and JS
```

## License

MIT License
