# g(it) d(iff) ex(plorer)

> Interactive `git diff` (branch compare) using [`fzf`](https://github.com/junegunn/fzf)

## Installation

CURL:

```sh
curl -o /usr/local/bin/gdex https://git.io/gdex && chmod 755 /usr/local/bin/gdex
```

npm:

```sh
npm install -g gdex
```

## Usage

```sh
$ gdex [<options>]
```

Type to fuzzy-search branches to compare.

Keys:

- **up/down**: navigate (click line also works)
- **ctrl-b**: create a branch from selected stash
- **del**: drop selected stash
- **enter**: view full diff (less)
- **esc**: exit gdex

## Related tools

[gsex](https://github.com/therealklanni/gsex) - g(it) s(tash) ex(plorer)

## License

MIT © Kevin Lanni

Modified from original work by [bturrubiates](https://github.com/bturrubiates/fzf-scripts).
