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
Create these preferences in about:config to customize your layout:
* Boolean:
  * **`gwfox.plus`**: Bundled layout (macOS UI + compact mode).
    * **`gwfox.plus_sc`**: Use native window controls.
  * **`gwfox.atbc`**: Enable compatibility with the **Adaptive Tab Bar Colour** extension.
  * **`gwfox.noborder`**: Remove window borders.
  * **`gwfox.icons`**: Enable menu icons.
  * **`gwfox.ac`**: Enable accent color (*Edit --bg0 in `.css` files to customize*).

* Number:
  * **`gwfox.sidebar`**: Set to **1**, **2**, or **3** for sidebar width.

