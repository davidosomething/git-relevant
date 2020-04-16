# git-relevant

| Name          | Link     |
| ------------- | -------- |
| Project Home: | [https://github.com/davidosomething/git-relevant](https://github.com/davidosomething/git-relevant)

## About

Output list of file paths relevant to what you're working on. I.e., files
that:

- are in the project but not tracked (new)
- have been modified (staged or not)
- are not merged into a given branch (master by default)

My typical usage is as a recently used files list for Vim/fzf

## Installation

- Requires BASH 4+
- Add the `git-relevant` file somewhere in your path, e.g. `/usr/local/bin/`

### zinit installation

Super simple if you use zplug:

```sh
zinit load "davidosomething/git-relevant"
```

## Usage

From command line execute:

```sh
git relevant
```

### Options

- `--branch [ref]`

Example:

```sh
git relevant --branch main
```

Compare against [ref] instead of master

## License

MIT Licensed
