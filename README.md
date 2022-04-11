# AngularWebComponent

To test either you can support Web component:

- in root of the project run `npm ci`
- in root of the project tun `npm start`
- copy following HTML code to your widget

```html
<test-element></test-element>
<script src="http://localhost:4200/runtime.js" type="module"></script>
<script src="http://localhost:4200/polyfills.js" type="module"></script>
<script src="http://localhost:4200/styles.js" defer></script>
<script src="http://localhost:4200/vendor.js" type="module"></script>
<script src="http://localhost:4200/main.js" type="module"></script>
```

- see `index.html` in root for reference
