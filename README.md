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

## Limitations

If something is wrong we welcome reports. However, due to procedural limitations we won't be accepting pull requests.
This repo is intended to be automatically generated as a build artifact linking backend scrapers to frontend documentation.

## Sources & Copyright

All flowcharts in this project are built from official project documentations.
If you believe that a source is not cited correctly or that something is compiled in violation of a copyright terms,
please open an issue here and we will try to resolve the issue as quickly as possible.
