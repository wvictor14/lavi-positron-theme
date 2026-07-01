# Lavi

Dark purple Positron/VS Code theme, ported from [lavi tmTheme](https://github.com/b0o/lavi).

## Install

### Open VSX (Positron, VS Code OSS)

Search for "Lavi" in Extensions panel (`Ctrl+Shift+X`), or install from [Open VSX](https://open-vsx.org/extension/wvictor14/lavi-positron-theme).

### VSIX (manual)

```
vsce package
# or download .vsix from GitHub Releases
positron --install-extension lavi-positron-theme-*.vsix
```

### VS Code Marketplace

Search for "Lavi" in Extensions view, or install from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=wvictor14.lavi-positron-theme).

## Activate

`Ctrl+K Ctrl+T` → select **Lavi**.

## Colors

| Role | Hex | Source |
|---|---|---|
| Editor bg | `#25213B` | lavi background |
| Foreground | `#EDE7FE` | lavi foreground |
| Purple accent | `#BDA5EE` | keywords, caret |
| Mint | `#9CF2DE` | functions |
| Green | `#DBFFB3` | strings |
| Orange | `#FF9A6B` | numbers |
| Teal | `#2CEDC0` | constants |
| Blue | `#94C8FF` | properties |

Full palette in `themes/lavi-color-theme.json`.

## Development

```
npm install -g @vscode/vsce
vsce package
positron --install-extension lavi-positron-theme-*.vsix
```

Or open folder in Positron and press `F5` (Extension Development Host).

## Publish

```
vsce publish
# then publish to Open VSX:
# npx ovsx publish -p <token>
```
