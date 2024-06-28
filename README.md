sublime-pyxy
============

<p align="center">
    <em>
        Originally created for PyXL: [yyjhao/sublime-pyxl](https://github.com/yyjhao/sublime-pyxl)
    </em>
</p>
<hr>

This is a work-in-progress.

## Installation

### Manual installation

1. Download the files using the GitHub.zip download option
2. Unzip the files to your Sublime Text Packages directory.

## Usage

After installing, set the syntax to `Python (pyxy)` for the file with pyxy
syntax.

## SublimeLinter

If you want to be able to lint the files with this syntax properly, go to
Preferences - Package Settings - SublimeLinter - Settings (User) and add the
following mapping to the `syntax_map`:

```json
    "syntax_map": {
        ...
        "python (pyxy)": "python",
        ...
    }
```
