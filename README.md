# Simple Tab Indent for Obsidian

**Tab** now inserts a zero-width space + real tab (`\u200B\t`).  
Because the first character isn’t whitespace, Markdown no longer turns the line into an indented code block, yet you keep a true tab width in the editor.

---

## ✨ Features

|                                                                                                 |     |
| ----------------------------------------------------------------------------------------------- | --- |
| 🔹 Replaces Obsidian’s default Tab handler with **ZWSP + Tab**.                                 |
| 🔹 Works in Source Mode and Live Preview.                                                       |
| 🔹 **Configurable tab width** – set any `tab-size` via the plugin’s settings panel (default 4). |
| 🔹 Zero build-step, zero runtime dependencies – just `manifest.json` & `main.js`.               |

---

## ⚙️ Configuration

`Settings ▸ Plugin options ▸ Simple Tab Indent`

- **Tab width** – number of spaces a tab should _render_ as (CSS `tab-size`, default 4).  
  Change the value, the editor updates instantly.

---

## 🩹 Troubleshooting

| Problem                                | Solution                                                                   |
| -------------------------------------- | -------------------------------------------------------------------------- |
| Plugin not listed                      | Check the folder path & manifest, then **Reload plugins**.                 |
| Another extension still intercepts Tab | Look in **Settings ▸ Hotkeys** for conflicting Tab bindings, disable them. |

---

## ⚠️ Important: Task Recognition Limitation

**Please be aware:** When you use this plugin to indent task lines or list items, those indented items will **not be recognized** by:

- Obsidian's built-in task management features
- Any task management plugins (like Tasks, Dataview, etc.)
- Obsidian's search when looking for tasks

**If you rely on task management features in Obsidian, consider whether this trade-off works for your workflow before enabling this plugin.**

---

## 📜 License

[MIT](LICENSE) • Made with ☕ by **Thiago Frias**
