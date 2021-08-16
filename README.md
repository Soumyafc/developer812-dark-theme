![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/Soumyafc/developer812-dark-theme?include_prereleases&style=for-the-badge)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/Soumyafc/developer812-dark-theme/master?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/Soumyafc/developer812-dark-theme?style=for-the-badge)

<h3 align="center">Get the best dark theme into your VS Code.</h3>

---
### Java Script
![Java Script Image](ScreenShots\javascript.png)

### HTML
![HTML Image](ScreenShots\html.png)

### C++
![C++ Image](ScreenShots\C++(2).png)

### CSS
![CSS Image](ScreenShots\css.png)

The most epic dark theme meets Visual Studio Code. You can help by reporting issues [here](https://github.com/Soumyafc/developer812-dark-theme/issues).

- [Getting started](#getting-started)
  - [Installation](#installation)
    - [GitHub Repository Clone](#github-repository-clone)
- [Activate theme](#activate-theme)
- [Override theme colors](#override-theme-colors)
  - [Color Scheme override](#color-scheme-override)
- [Recommended settings for a better experience](#recommended-settings-for-a-better-experience)
- [Other resources](#other-resources)

## Getting started

You can install this theme through the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=developer812.developer812-dark-theme&ssr=false#overview).

### Installation

Launch _Quick Open_:

- <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
- <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`
- <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste the following command and press `Enter`:

```shell
ext install developer812 theme
```

And pick the one by **developer812** .

### GitHub Repository Clone

```shell
git clone https://github.com/Soumyafc/developer812-dark-theme.git
```

## Activate theme

Click on the `Settings(gear) icon` at the very bottom of the `activity bar` and then you choose `Color Theme` option , then find out `developer812 dark theme` option and click it.




## Override theme colors

You can override the developer812 Theme UI and schemes colors by 
Launch _Quick Open_:

- <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
- <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`
- <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste `settings.json` and press `Enter`:


[relative section on the VS Code documentation](https://code.visualstudio.com/docs/getstarted/themes#_customizing-a-color-theme).

### Color Scheme override

```js
// Overrides colors
"workbench.colorCustomizations": {
    "[developer812 dark theme]": {
        "sideBar.background": "#14213d",
    }
},

// Overrides editor syntax colors and font style
"editor.tokenColorCustomizations": {
    "[developer812 dark theme]": {
        "comments": "#229977",
    }
},
```

## Recommended settings for a better experience

```js
{
    // Controls the font family.
    "editor.fontFamily": "Roboto Mono",
    // Controls the font size.
    "editor.fontSize": 20,
    // Controls if file decorations should use badges.
    "explorer.decorations.badges": false
}
```

## Other resources

- Please review about this theme to help us to make this theme better for you  [Google Form](https://forms.gle/tzYxqShzE356oiaU7) .

---
