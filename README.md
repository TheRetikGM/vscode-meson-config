# vscode-meson-config
Automatically generate vscode config files based on meson build files.

## Usage
1. Create a wrap file or clone this into subprojects directory
2. Add `subproject('vscode-meson-config')` to the meson.build

## :exclamation: Caution :exclamation:
For now, the executable name must be `main` or you must change it in the generated .vscode/settings.json


