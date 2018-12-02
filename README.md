# Bootstrap-Cookie-Alert
A simple, good looking cookie alert build for Bootstrap 4. No dependencies required.

[Demo](https://wruczek.github.io/Bootstrap-Cookie-Alert/demo)

I unfortunately dont remeber the source of the cubes pattern :(
If someone know, please email me or create an issue. I would love to credit the author.

## npm package
`npm i bootstrap-cookie-alert`<br>
I try to keep it up-to-date. Let me know if I forget to release an update.

## How to use
#### 1. In the `head` of your document, include `cookiealert.css` **after Bootstrap**.
```html
<link rel="stylesheet" href="cookiealert.css">
```

#### 2. Add the html markup:
```html
<!-- START Bootstrap-Cookie-Alert -->
<div class="alert text-center cookiealert" role="alert">
    <b>Do you like cookies?</b> &#x1F36A; We use cookies to ensure you get the best experience on our website. <a href="https://cookiesandyou.com/" target="_blank">Learn more</a>

    <button type="button" class="btn btn-primary btn-sm acceptcookies" aria-label="Close">
        I agree
    </button>
</div>
<!-- END Bootstrap-Cookie-Alert -->
```

#### 3. Include the JavaScript after the html markup
```html
<script src="cookiealert.js"></script>
```
### Take a look at [`demo.html`](https://github.com/Wruczek/Bootstrap-Cookie-Alert/blob/gh-pages/demo.html) for a working example
