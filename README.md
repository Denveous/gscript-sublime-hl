# gscript-sublime-hl

`gscript-sublime-hl` is a Sublime Text syntax highlighting configuration for the GraalScript language, widely used in server and system scripts for the game Graal Online. The file automatically detects `.gs2`, `.graalscript`, `.graalscript2`, `.gs`, `.gscript`, and `.gscript2` files and applies syntax highlighting, making it easier to read and edit these scripts.

## Features

- Syntax highlighting for GraalScript commands, functions, operators, and keywords
- Support for line and block comments
- Detection and highlighting of SQL queries inside strings
- Highlighting for built-in variables like `this`, `server`, `client`, `player`
- Support for control flow keywords: `if`, `else`, `for`, `while`, `switch`, etc.
- Number detection (decimal and hexadecimal)

## Installation

1. Download `graalscript.sublime-syntax` from this repository
2. Copy the file to your Sublime Text Packages/User directory:
   - **Windows**: `%APPDATA%\Sublime Text\Packages\User\`
   - **macOS**: `~/Library/Application Support/Sublime Text/Packages/User/`
   - **Linux**: `~/.config/sublime-text/Packages/User/`
3. Restart Sublime Text or reopen any GraalScript files

## Usage

Once installed, syntax highlighting will automatically apply to any `.gs2`, `.graalscript`, `.graalscript2`, `.gs`, `.gscript`, or `.gscript2` file. You can also manually select the syntax by:

1. Opening the file
2. Clicking on the syntax name in the bottom-right corner
3. Selecting "graalscript" from the list

## File Extensions

By default, this syntax highlighting applies to `.gs2`, `.graalscript`, `.graalscript2`, `.gs`, `.gscript`, and `.gscript2` files. If you need to apply it to different file extensions, you can modify the `file_extensions` section in the `graalscript.sublime-syntax` file.
