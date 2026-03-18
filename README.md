<div align="center">
<picture>
<source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/680c10b1-c8bc-4d60-8dfb-3ac4c49920b2">
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/e0fe0c3f-4fb8-4123-b745-0557cdb3be64">
<img alt="Preview">
</picture><br><br>
<a href="https://github.com/akkva/gwfox/archive/refs/heads/main.zip"><img alt="GWfox" src="https://img.shields.io/badge/GWfox-3.0-blue?style=for-the-badge"/></a>
<a href="https://www.firefox.com"><img alt="Firefox" src="https://img.shields.io/badge/Firefox-149-blue?style=for-the-badge"/></a>
</div>

## Installation
1. Download the theme and move the `chrome` folder into your Firefox **profile directory**.
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
3. **Restart Firefox.**

## Customization
To enable additional features, add these **Boolean** preferences in `about:config` and set them to **`true`**:
* **`gwfox.plus`**: Enables a bundled layout featuring macOS-style window controls, compact mode, a sidebar-integrated address bar, and an auto-hiding Bookmarks Toolbar.
    * **`gwfox.plus_sc`**: Use native window controls.
* **`gwfox.atbc`**: Enables compatibility with the **Adaptive Tab Bar Colour** extension.
* **`gwfox.noborder`**: Removes window borders.
* **`gwfox.icons`**: Enables menu icons.

## Sidebar
In `about:config`, create a new **Number** preference named **`gwfox.sidebar`** with a value of **1**, **2**, or **3** to configure the sidebar width.

## Accent Color
1. In `about:config`, create a new **Boolean** preference named **`gwfox.ac`** and set it to **`true`**.
2. Locate the `--bg0` variable in `userChrome.css` and `userContent.css`, and change its value to your preferred color.

