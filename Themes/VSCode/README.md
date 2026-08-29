# MGRUV for VS Code

A muted, warm dark theme with a clean Gruvbox-like character. It is designed around the supplied MGRUV palette: warm charcoal surfaces, sand-colored text, and softened red, green, gold, blue, teal, and mauve accents.

## Install from this folder

1. Copy `mgruv-vscode-theme` into a convenient location.
2. In VS Code, open **Extensions** → **…** → **Install from VSIX…** if you have the packaged `.vsix`, or use the extension development workflow with this folder.
3. Select **MGRUV** from **Preferences: Color Theme**.

The folder is also ready to package with `npx @vscode/vsce package` from its root.

## Palette mapping

| Role | Color |
| --- | --- |
| Editor background | `#1E2021` |
| Raised surface | `#30302D` |
| Border / selection | `#47433A` / `#5C6439` |
| Primary text | `#D4C2A0` |
| Bright text | `#E8DCB6` |
| Muted text | `#B8A98A` / `#818383` |
| Gold accent | `#C6A15B` |
| Green accent | `#86A987` |
| Red accent | `#C58B8B` |
| Blue accent | `#7E9FC0` |
| Teal accent | `#7BA6A3` |
| Mauve accent | `#9B829B` |

The key supplied ramp values are preserved directly: `#3A3832`, `#47433A`, `#B8A98A`, `#D4C2A0`, and `#E8DCB6`.
