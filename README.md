# Template go Repository

## tl;dr

This is a template go repository with actions already set up to create compiled releases

## What does this Template provide?

* a basic cli application with subcommands based on [Kong](https://github.com/alecthomas/kong)
* logging using zerolog
* some customisations like a more descriptive version info
* A sample for a spinner
* GitHub workflow to run tests on every push
* GitHub Workflow to build binary releases with [goreleaser](https://github.com/goreleaser/goreleaser)

## What is missing?

* some sample code for a cli interactive selection dialogue using [promptui](https://github.com/manifoldco/promptui)
## How to use this template

```bash
git clone https://github.com/gentoomaniac/go-template.git ./
rm -r .git
git init
git add -A
git commit -m 'import template'
```
