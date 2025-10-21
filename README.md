# Shiro Language Support for VS Code

Syntax highlighting for the Shiro programming language.

## Features

- Syntax highlighting for `.shiro` files

## Installation

### Option 1: Install from source (Development)

1. Copy this folder to your VS Code extensions directory:
   - **Windows**: `%USERPROFILE%\.vscode\extensions\`
   - **macOS/Linux**: `~/.vscode/extensions/`

2. Restart VS Code (NOTE: When updating the addon, it's enough to Ctrl+Shift+P -> "Developer: Reload Window")

3. Open any `.shiro` file to see syntax highlighting

### Option 2: Install using vsce (Package as .vsix)

1. Install vsce:
   ```bash
   npm install -g @vscode/vsce
   ```

2. Package the extension:
   ```bash
   vsce package
   ```

3. Install the generated `.vsix` file:
   - Open VS Code
   - Go to Extensions (Ctrl+Shift+X / Cmd+Shift+X)
   - Click "..." menu → "Install from VSIX..."
   - Select the generated `.vsix` file

## License

MIT
