# canvax
>Simple, lightweight, entity-based canvas library

---

[Full documentation](https://futuristiccake.github.io/canvax/) | [NPM](https://www.npmjs.com/package/canvaxjs)

### Use canvax

It's super simple, mate. Just insert the JS file like so.

```html
<!-- ... -->
<head>
	<script src="canvax.js" defer></script>
</head>
<!-- ... -->
```

### Really use Canvax

Okay, so the Canvax library is really simple to use. To create a new renderer, go ahead and attach the thing to the canvas element.

```javascript
var game = new canvax.Renderer(document.querySelector("canvas"));
```

Let's render a rectangle on the canvas. Super simple.

```javascript
game.add(new canvax.Rectangle(0, 0, 100, 100));
game.render();
```

### Full Documentation

You can find the full documentation over [here](https://futuristiccake.github.io/canvax/)!

### Install canvax

```
npm install canvaxjs
```

... and then simply include the library in your page like so...

```html
<script src="node_modules/canvaxjs/canvax.min.js"></script>
```