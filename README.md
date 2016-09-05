# devtools
Me trying to find ways to make my life better

### Installation
Run `git clone git@github.com:Desmaster/devtools.git` and add that directory to your `$PATH` variable

### Commands

##### semvup

Ups your current version in the files that you have specified.

Make sure you have a `.semver` file in your project directory that looks like this: 

```
[default]
version = 1.0.0
files = file.json, file.xml
```

Then run `semvup (patch|minor|major)`.

This command is work in progress, it supports the following files:

- `composer.json`

