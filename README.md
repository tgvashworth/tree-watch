# tree-watch

Yet another file watcher.

Write a path to all files that match a glob within a directory to stdout, and again when they change.

```
$ npm install -g tree-watch
```

## Usage

```
$ tree-watch . "**/*.js"
./index.js
./lib/something.js
```

Then when you change `index.js`:

```
./index.js
```

## License

MIT

