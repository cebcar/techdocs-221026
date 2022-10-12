#Codium
*VS Code: Open-source code editor*
  (VS Codium is a binary releases of VS Code without MS branding/telemetry/licensing)

## Configuration
### Installation
Homebrew: vscodium
Then, to add its binary to PATH:
``` zsh
cat << EOF >> ~/.zshrc
# Add VS Codium (codium)
export PATH="\$PATH:/Applications/vscodium.app/Contents/Resources/app/bin/codium"
EOF
```

### Preferences
- Settings
  - Editor
    - Tab Size: 2
    - Render Whitespace: all
    - Minimap: off
- Keyboard Shortcuts
  - open Terminal: 	ros`
    *where is this command?*

### Keyboard Shortcuts
- Explorer		scE
- Search / Find 	scF
- Source Control	rsG
- Run &amp; Debug	scD
- Extensions		scX

### Launching from the command line
- find Shell Commands
  - Command Commands: Palette (csP): search for "shell"
    - Shell Command: install 'codium' command in PATH

