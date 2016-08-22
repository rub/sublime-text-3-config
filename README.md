Sublime Text 3 Config
=====================

This is my Sublime Text 3 configuration for front end development.

Install Package Control
-----------------------

Install [Package Control](https://packagecontrol.io/) for easy package management.

Customize the UI
----------------

Install [Seti_UI](https://packagecontrol.io/packages/Seti_UI) and [Spacegray](https://github.com/kkga/spacegray) themes to redifine the whole UI and add a new syntax highlighting.

Install the packages
--------------------

To install a package hold `⌘` + `Shift` + `P` and type install, then start typing the name of the you need to install.

### General
* [AdvancedNewFile](https://packagecontrol.io/packages/AdvancedNewFile) - Faster file creation within a project.
* [AutoFileName](https://packagecontrol.io/packages/AutoFileName) - Autocomplete filenames.
* [Gutter Color](https://packagecontrol.io/packages/Gutter%20Color) - Displays a color in the gutter if the line contains a color.
* [SideBarEnhancements](https://packagecontrol.io/packages/SideBarEnhancements) - Provides enhancements to the operations on sidebar of files and folders.

### HTML, CSS, JavaScript
* [Babel](https://packagecontrol.io/packages/Babel) - Syntax definitions for ES6 JavaScript with React JSX extensions.
* [CSS3](https://packagecontrol.io/packages/CSS3) - More complete CSS support.
* [HTML5](https://packagecontrol.io/packages/HTML5) - Adds HTML5 syntax and snippets.
* [Sass](https://packagecontrol.io/packages/Sass) - Sass support.

### Git
* [GitGutter](https://packagecontrol.io/packages/GitGutter) - Shows git diff in the gutter.

### Markdown
* [Markdown Preview](https://packagecontrol.io/packages/Markdown%20Preview) - Markdown files preview and build in your web browser.
* [Markdown Extended](https://packagecontrol.io/packages/Markdown%20Extended) - Markdown syntax highlighter.
* [WordCount](https://packagecontrol.io/packages/WordCount) - Provides a real-time Word Count and character count in the status-bar.

Settings - User
---------------

Place the below custom user settings into Settings - User, accessible via `SublimeText` → `Preferences`→ `Settings - User`, or by holding `⌘` + `,`.

```json
{
  "auto_complete_commit_on_tab": true,
  "auto_complete_with_fields": true,
  "bold_folder_labels": true,
  "caret_extra_bottom": 2,
  "caret_extra_top": 2,
  "caret_extra_width": 2,
  "caret_style": "solid",
  "color_scheme": "Packages/Theme - Spacegray/base16-ocean.dark.tmTheme",
  "draw_minimap_border": true,
  "ensure_newline_at_eof_on_save": true,
  "font_size": 14,
  "highlight_line": true,
  "highlight_modified_tabs": true,
  "ignored_packages":
  [
    "CSS",
    "Vintage"
  ],
  "indent_guide_options":
  [
    "draw_normal",
    "draw_active"
  ],
  "line_padding_bottom": 2,
  "line_padding_top": 2,
  "match_brackets_angle": true,
  "save_on_focus_lost": true,
  "tab_size": 2,
  "theme": "Seti.sublime-theme",
  "translate_tabs_to_spaces": true
}
```

Packages Settings
-----------------

Each of the following configuration snippets refers to a specific package, accessible via `Sublime Text` → `Preferences` → `Package Settings` → *`package name`* → `Settings - User`.

##### AdvancedNewFile
```json
{
  "default_root": "current",
}
```

Launch Sublime Text 3 from the command line
-------------------------------------------

From your terminal, run:
`ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/sublime`

Then run `sublime --help` to show the helper.

Run `sublime .` to open the entire current directory.
