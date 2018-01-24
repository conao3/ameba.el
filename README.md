## ameba.el
*An Emacs interface to [Ameba](https://github.com/veelenga/ameba)*

---
[![License GPLv3](https://img.shields.io/badge/license-GPL_v3-green.svg)](http://www.gnu.org/licenses/gpl-3.0.html)

[Ameba](https://github.com/veelenga/ameba) is a static code analysis tool
for [Crystal](https://crystal-lang.org/).

This package allows you to use this tool directly in Emacs.

### Features:

* Allows to run Ameba on the currently visited file
* Allows to run Ameba on the entire project
* Allows to prompt from a directory on which to run Ameba
* Flycheck mode

### Usage

Run one of the predefined interactive functions.

See [Function Documentation](#function-documentation) for details.

### Function Documentation


#### `(ameba-check-current-file)`

Run check on the current file.

#### `(ameba-check-project)`

Run check on the current project.

#### `(ameba-check-directory &optional DIRECTORY)`

Run check on the DIRECTORY if present or prompt user if not.

-----
<div style="padding-top:15px;color: #d0d0d0;">
Markdown README file generated by
<a href="https://github.com/mgalgs/make-readme-markdown">make-readme-markdown.el</a>
</div>
