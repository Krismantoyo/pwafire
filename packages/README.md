## Introducing *pwafire* cdn and npm 

 All New Web Capabilities as one Package! All APIs bundled together.

### Install pwafire via NPM

```bash
 npm i pwafire
```

### Get pwafire over CDN

```html
<!-- Insert this script at the bottom of the HTML, but before you use any PWA Capability -->
<script src="https://pwafire.org/code/cdn/releases/@latest/pwafire.js"></script>
```
### Example : using *pwafire*

#### Import pwafire in your react app

```js
 import pwafire from "pwafire";
 const pwa = pwafire.pwa;
```

#### Call the share method on pwa

```js
 pwa.Share(element, data);
```

### Get started

 - Over [NPM docs](https://github.com/pwafire/pwafire/tree/master/packages/npm)
 
 - Over [CDN docs](https://github.com/pwafire/pwafire/tree/master/packages/cdn)
