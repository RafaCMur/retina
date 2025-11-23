# Retina Theme - Quick Guide

## Project Structure

- `package.json` - Extension manifest
- `themes/Retina-theme.json` - Color theme definition

## Test Your Theme

1. Press `F5` to open a new window with your extension loaded
2. Open theme selector: `Ctrl+K Ctrl+T`
3. Select "Retina"

## Package as VSIX

### 1. Install vsce

```bash
npm install --save-dev @vscode/vsce
```

### 2. Generate VSIX

```bash
npx vsce package
```

This creates `retina-0.0.6.vsix`

### 3. Test VSIX

1. Go to Extensions in VS Code
2. Click "..." and select "Install from VSIX"
3. Choose your `.vsix` file

### 4. Publish (optional)

```bash
npx vsce publish
```

You need a token from VS Code Marketplace

## Make Changes

Changes to the theme file are automatically applied in the development window.
