<div align="center">
<picture>
<source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/968b1f8b-8047-4aff-86f9-bf77f0affc36">
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/9d5373c0-8abb-42ec-a78c-e40398f2d334">
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

To enable additional features and layouts, modify your `about:config` settings as described below.

### 1. Boolean Preferences
Create the following **Boolean** preferences and set them to **`true`**:

* **`gwfox.plus`**: Enables a bundled layout featuring macOS-style window controls, compact mode, a sidebar-integrated address bar, and an auto-hiding Bookmarks Toolbar.
    * **`gwfox.plus_sc`**: Use native window controls instead.
* **`gwfox.atbc`**: Enables compatibility with the **Adaptive Tab Bar Colour** extension.
* **`gwfox.noborder`**: Removes window borders.
* **`gwfox.icons`**: Enables menu icons.
* **`gwfox.ac`**: Enables the custom accent color. 
    * *Optional: To change the default color, locate the `--bg0` variable in `userChrome.css` and `userContent.css` and change its value.*

### 2. Number Preference
Create the following **Number** preference to configure the sidebar:

* **`gwfox.sidebar`**: Set the value to **1**, **2**, or **3** to adjust the sidebar width.

