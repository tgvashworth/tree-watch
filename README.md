# tree-watch

Write a path to all files that match a glob within a directory to stdout, and again when they change.

```
$ npm install tree-watch
```

### Usage

```
$ tree-watch . "*.js"
./index.js
./lib/something.js
```

Then when you change `index.js`:

```
./index.js
```


