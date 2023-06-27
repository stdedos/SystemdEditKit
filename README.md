# Systemd Edit Kit for Sublime Text

This package provides POC support for systemd files in Sublime Text.

Features include syntax highlighting, comment toggling, and highlighting for booleans and strings.

## Features

- Syntax highlighting for systemd service, target, and timer files
- Comment toggling using both `#` and `;` as comment delimiters
- Proper handling of strings, including support for continuation lines
- Highlighting for boolean values (`yes`, `no`, `0`, `1`, `true`, `false`)

## Installation

1. Download the zip file from this repository and unzip it, or clone the repository using git.
2. Open Sublime Text, go to `Preferences -> Browse Packages` to open the `Packages` directory.
3. Move the unzipped folder (or cloned repository) into the `Packages` directory.
4. Restart Sublime Text. The new syntax should now be available.

## Usage

Once installed, Sublime Text will automatically use the Systemd Enhanced Editor for Systemd files.
You can also manually select the syntax by going to `View -> Syntax -> Systemd` in Sublime Text.

## Contributing

Contributions are welcome! Please open an issue if you encounter any problems, or a pull request if you make improvements to the package.

Kindly try to also provide tests for your improvements - preferably including the issue / pull request number in the filename (`<issue number>.<ext>`.)
