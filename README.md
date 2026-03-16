<div align="center">
<picture>
<source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/204bffdb-d37f-4a3e-98f6-c21e84b3b46d">
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/0a83cfb1-23ac-4458-8113-536b240d549b">
<img alt="Preview">
</picture><br><br>
<a href="https://github.com/akkva/gwfox"><img alt="GWfox" src="https://img.shields.io/badge/GWfox-blue?style=for-the-badge"/></a>
<a href="https://www.firefox.com"><img alt="Firefox" src="https://img.shields.io/badge/Firefox-149-blue?style=for-the-badge"/></a>
</div>

## Installation
1. **[Download the theme](https://github.com/akkva/gwfox/archive/refs/heads/main.zip)** and move the `chrome` folder into your Firefox **profile directory**.
2. Navigate to `about:config` and configure the following preferences:
    * **Set to `true`**:
        * `toolkit.legacyUserProfileCustomizations.stylesheets`
        * `svg.context-properties.content.enabled`
        * `widget.windows.mica` (*Windows; requires **System theme — auto** to work*)
    * **Set to `false`**:
        * `sidebar.animation.enabled`
        * `widget.macos.native-context-menus` (*macOS*)
    * **Set to `2`**:
        * `widget.windows.mica.toplevel-backdrop` (*Windows*)
5. **Restart Firefox.**

## Customization
To enable additional features, add these **Boolean** preferences in `about:config` and set them to **`true`**:
* **`gwfox.plus`**: Enables a bundled layout featuring macOS-style window controls, compact mode, a sidebar-integrated address bar, and an auto-hiding Bookmarks Toolbar.
    * **`gwfox.plus_sc`**: Use native window controls.
* **`gwfox.atbc`**: Enable compatibility with the **Adaptive Tab Bar Colour** extension.
* **`gwfox.noborder`**: Remove window borders.
* **`gwfox.icons`**: Enable menu icons.

## Customizing Accent Color
1. In `about:config`, add a new **Boolean** preference named **`gwfox.ac`** and set it to **`true`**.
2. Locate the `--bg0` variable in `userChrome.css` and `userContent.css`, and change its value to your preferred color.

