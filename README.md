# Software Flowcharts

How to do X in Y. This is middleware of the [LibExplainer.com](https://www.libexplainer.com) project.

## Format

Currently efforts are being made to document installation of a variety of projects on GitHub.
Each project gets an install.yaml file in `github/username/project` to describe the installation process.

## Example install.yaml

```
windows:
  shell: "cargo install lsts"
linux:
  shell: "cargo install lsts"
macos:
  shell: "cargo install lsts"
```

## What about Makefiles etc?

Some installation steps might not be terminal commands.
For example, an installation step might include "click on this button" or "fill in this text field".
These steps need a new standard, so we will throw them into a yaml file.
