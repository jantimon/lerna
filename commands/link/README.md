# `@lerna/link`

> Symlink together all packages that are dependencies of each other

## Usage

```sh
$ lerna link
```

Symlink together all Lerna `packages` that are dependencies of each other in the current Lerna repo.

## Options

### `--force-local`

```sh
$ lerna link --force-local
```

When passed, this flag causes the `link` command to always symlink local dependencies regardless of matching version range.
