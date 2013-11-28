# tree-watch

Yet another file watcher.

Write to stdout all matching files, and again when they change or when new files are added.

```
$ npm install -g tree-watch
```

## Usage

```
$ tree-watch . "**/*.js"
./index.js
./lib/something.js
```

When you change `index.js`:

```
./index.js
```

When you add `lib/another.js`:

```
./lib/another.js
```

When you delete `lib/another.js`:

```
./lib/another.js
```

You get the idea.

## Options

Defaults to relative paths, but supports `--absolute` flag to get full path.

## License

MIT

