https://cheatsheetmaker.com/watchman

### Also see

 * [Documentation](https://facebook.github.io/watchman/docs/install.html) _(facebook.github.io)_### Watching

```
watchman watch ~/src
watchman watch-list
watchman watch-del ~/src
```
### Getting started

```bash
watchman watch ./src
```

Adds `./src` to the watch list.

```bash
watchman -- trigger ./src retest '*.js' -- npm test
```

Adds a trigger called `retest` to run `npm test` every time `*.js` changes in `./src`.
