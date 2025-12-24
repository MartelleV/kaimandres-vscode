# Kaimandres for VS Code

![Preview](images/1.png)
![Preview](images/2.png)

<div align="center">
  <p>
    <strong>A robust, high-contrast, semantic theme; a crossover between Poimandres and Kanagawa aesthetics.</strong>
  </p>

  <p>
    <a href="https://github.com/MartelleV/kaimandres-vscode/stargazers"><img src="https://img.shields.io/github/stars/MartelleV/kaimandres?style=for-the-badge&colorA=16161e&colorB=78a9ff" alt="Stars"></a>
    <a href="https://github.com/MartelleV/kaimandres-vscode/blob/main/LICENSE"><img src="https://img.shields.io/github/license/MartelleV/kaimandres?style=for-the-badge&colorA=16161e&colorB=d0679d" alt="License"></a>
  </p>
</div>

---

## Philosophy

Kaimandres is handcrafted by me for the "deep void" that balances the renowned sleek aesthetics of **Poimandres** with the robust semantic logic and dimming capabilities of **Kanagawa**. 

## Features

- **Semantic Highlighting:** Full support for VS Code's Semantic Token system for TypeScript, Rust, Go, Python, Lua, and more - almost any language that you can think of or work with!
- **Deep Immersion:** The UI blends seamlessly with the editor canvas using the `inkBlack` and `voidBlack` palette.
- **Rich Workbench:** Custom styling for the Activity Bar, Side Bar, Panels, and Terminals to match the Neovim and Terminal experience exactly.
- **Focus:** Italics are used sparingly for keywords and comments to create a flow, while bolding is reserved for control flow.

## Installation

1. Open the **Extensions** sidebar in VS Code.
2. Search for `Kaimandres`.
3. Click **Install**.
4. Open the **Command Palette** (`Ctrl+Shift+P` or `Cmd+Shift+P`).
5. Type `Preferences: Color Theme` and select **Kaimandres**.

## The Neovim Original

This theme is a direct port of my original Neovim implementation. If you are a Neovimmer like me, check it out as well: **[kaimandres.nvim](https://github.com/MartelleV/kaimandres.nvim)**.

## Recommended Settings

For the full Kaimandres experience, add these to your `settings.json`:

```json
{
  "editor.fontFamily": "JetBrains Mono",
  "editor.cursorBlinking": "smooth",
  "editor.semanticHighlighting.enabled": true,
  "editor.renderLineHighlight": "all",
  "workbench.iconTheme": "catppuccin-mocha", // Recommended file icon theme
}
```

## Acknowledgements

This project, just like its Neovim counterpart, has been built based on many inspirations. Special thanks to:

- **[Rebelot](https://github.com/rebelot)** for creating **Kanagawa.nvim** and inspired me with the incredible architecture and logic.
- **[Poimandres](https://github.com/drcmda/poimandres-theme)** developers for the original VS Code theme and the beautiful color theory.
- **[The iTerm2 Color Scheme Community](https://github.com/mbadolato/iTerm2-Color-Schemes)** for introducing me to this aesthetic.

## License

MIT © MartelleV.