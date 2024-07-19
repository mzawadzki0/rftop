# rftop

A simple wrapper script for `rm -rf`.

It displays a summary of counts and sizes, as well as **a single prompt for confirmation**.

# Prerequisites

**dutree** 

https://github.com/nachoparker/dutree

**tree**

from your distro's package manager.

# Installation

```
git clone https://github.com/mzawadzki0/rftop
cd rftop
chmod u+x rftop
```
...and symlink the file to one of the direcories in PATH.

# Usage

Each name, path or wildcard from the arguments is checked for validity against existing files, and is later passed to `rm` directly.

**It only asks once for confirmation. All arguments are treated as file names.**

**Use at your own risk.**

```
$ rftop file1 [file2 ...]
```
