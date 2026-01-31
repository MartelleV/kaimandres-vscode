# Kaimandres for VS Code

<div align="center">
  <strong>A robust, high-contrast, semantic theme; a crossover between Poimandres and Kanagawa aesthetics.</strong>

  [![Version](https://img.shields.io/visual-studio-marketplace/v/martellev.kaimandres-vscode?style=flat-square&color=5a4a78)](https://marketplace.visualstudio.com/items?itemName=martellev.kaimandres-vscode)
  [![Installs](https://img.shields.io/visual-studio-marketplace/i/martellev.kaimandres-vscode?style=flat-square&color=76946a)](https://marketplace.visualstudio.com/items?itemName=martellev.kaimandres-vscode)
  [![Rating](https://img.shields.io/visual-studio-marketplace/r/martellev.kaimandres-vscode?style=flat-square&color=c4746e)](https://marketplace.visualstudio.com/items?itemName=martellev.kaimandres-vscode)
  [![License](https://img.shields.io/github/license/MartelleV/kaimandres-vscode?style=flat-square&color=7e9cd8)](LICENSE)

  <br />

  <p align="center">
    <img src="images/1.png" width="48%" alt="Preview 1" />
    <img src="images/2.png" width="48%" alt="Preview 2" />
  </p>
</div>

---

## Philosophy

> Kaimandres is handcrafted by me for the "deep void" that balances the renowned sleek aesthetics of **Poimandres** with the robust semantic logic and dimming capabilities of **Kanagawa**.

---

## Features

* **Semantic Highlighting:** Full support for VS Code's Semantic Token system for TypeScript, Rust, Go, Python, Lua, and more - almost any language that you can think of or work with!
* **Deep Immersion:** The UI blends seamlessly with the editor canvas using the `inkBlack` and `voidBlack` palette.
* **Rich Workbench:** Custom styling for the Activity Bar, Side Bar, Panels, and Terminals to match the Neovim and Terminal experience exactly.
* **Focus:** Italics are used sparingly for keywords and comments to create a flow, while bolding is reserved for control flow.

---

## Installation

1. Open the **Extensions** sidebar in VS Code (`Ctrl+Shift+X`).
2. Search for `Kaimandres`.
3. Click **Install**.
4. Open the **Command Palette** (`Ctrl+Shift+P`).
5. Type `Preferences: Color Theme` and select **Kaimandres**.

---

## Other Ports

If you are a Zed user, go here: **[Kaimandres Zed Theme](https://zed-themes.com/themes/-NvUnJul7Bvewn1wS29Ff?name=Kaimandres)** and download the theme's JSON file, then put it inside your `~/.config/zed/themes` directory.
Or better yet, you can download it directly from Zed's Extension Market. The theme is now officially published on Zed.

---

## The Neovim Original

This theme is a direct port of my original Neovim implementation. If you are a Neovimmer like me, check it out as well: **[kaimandres.nvim](https://github.com/MartelleV/kaimandres.nvim)**.

---

## Recommended Settings

For the full Kaimandres experience, add these to your `settings.json`.

<details>
  <summary>Click to expand settings</summary>

  ```json
  {
    "editor.cursorBlinking": "smooth",
    "editor.semanticHighlighting.enabled": false, // IMPORTANT: This allows the theme's full highlighting capability, as I set up every token granularly via Textmate to closely match Neovim's original.
    "workbench.iconTheme": "catppuccin-mocha", // Recommended file icon theme
  }

  ```

</details>

---

## Reporting Issues

If you encounter any bugs, visual inconsistencies, or unexpected behavior while using Kaimandres, please open an issue/PR, I will solve it ASAP.

When reporting an issue, please include:

* A clear description of the problem (e.g., with which language did you encounter this, steps to reproduce the problem)
* Screenshots, if applicable
* Your VS Code version and any relevant settings

---

## Acknowledgements

This project, just like its Neovim counterpart, has been built based on many inspirations. Special thanks to:

* **[Rebelot](https://github.com/rebelot)** for creating **Kanagawa.nvim** and inspired me with the incredible architecture and logic.
* **[Poimandres](https://github.com/drcmda/poimandres-theme)** developers for the original VS Code theme and the beautiful color theory.
* **[The iTerm2 Color Scheme Community](https://github.com/mbadolato/iTerm2-Color-Schemes)** for introducing me to this aesthetic.

---

## License

MIT © [MartelleV](https://github.com/MartelleV).
