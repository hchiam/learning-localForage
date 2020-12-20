# Learning [localForage](https://github.com/localForage/localForage)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

https://github.com/localForage/localForage

https://css-tricks.com/a-primer-on-the-different-types-of-browser-storage

https://codepen.io/hchiam/pen/MWepRZo or https://codepen.io/thgreasi/pen/ojYKeE

## From scratch

Using [`yarn`](https://github.com/hchiam/learning-yarn):

```bash
yarn add localforage
```

Or with `npm`:

```bash
npm install localforage
```

Or with CDN:

```html
<script src="https://cdn.rawgit.com/mozilla/localForage/master/dist/localforage.js"></script>
```

Then there are different ways to use localForage. Here's one way:

```js
localforage.setItem('key', 'value').then(function () {
  return localforage.getItem('key');
}).then(function (value) {
  console.log('success');
}).catch(function (err) {
  console.log('error');
});
```

## Starting by testing out this repo

Using [`yarn`](https://github.com/hchiam/learning-yarn): (triple-click to select all)

```bash
git clone https://github.com/hchiam/learning-localForage.git && cd learning-template && yarn; # and then ...
```

Or with `npm`: (triple-click to select all)

```bash
git clone https://github.com/hchiam/learning-localForage.git && cd learning-localForage && npm install; # and then ...
```
