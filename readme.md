git-spread
==========

Utility to run git commands across multiple children directories. Runs the specified git command against
all immediate subdirectories that contain a .git directory.

## Usage

```shell
$ git spread
usage: git spread <normal git commands>
  Use git-spread to run git commands across directorie
  e.g.
    git spread pull
    git spread commit -m 'updated .gitignore'
```

## Installation

Copy somewhere in your path eg `/usr/local/bin`
