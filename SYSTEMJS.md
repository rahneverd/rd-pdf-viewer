In your `system.config.js`

Append to `map`

```js
var map = {
  'rd-pdf-viewer': 'node_modules/rd-pdf-viewer/bundles',
  'pdfjs-dist': 'node_modules/pdfjs-dist',
};
```

and then add to `packages`

```js
var packages = {
  'rd-pdf-viewer': { defaultExtension: 'js', format: 'cjs' },
  'pdfjs-dist': { defaultExtension: 'js' },
};
```
