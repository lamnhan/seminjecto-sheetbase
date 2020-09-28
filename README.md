# Sheetbase Skeleton

Skeleton for building [Sheetbase](https://github.com/sheetbase) server app/module.

## Buiding an app

Clone this repo.

Or using the [Seminjecto](https://github.com/lamnhan/seminjecto):

```sh
# TODO
semidi new sheetbase [project_name]
```

See [Seminjecto](https://github.com/lamnhan/seminjecto) for more detail.

## Building a module

Do the same as building an app, then modify these:

- `package.json`: Rename the package to whatever but not `@sheetbase/backend` or prefixed with `@app/<name>`. Remove `@sheetbase/server` from dependency.
- `appsscript.json`: Remove the `webapp` property.
- Delete `src/app/` and `src/www.ts`.

## License

**@sheetbase/skeleton** is released under the [MIT](https://github.com/sheetbase/skeleton/blob/master/LICENSE) license.
