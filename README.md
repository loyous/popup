# Popup.js

---

## Installation

Place `/assets/css/popup.css` in `/your/css/folder/`.

Add this just before your closing `head` tag:

```html
<link rel="styesheet" href="/your/css/folder/popup.css">
```

Then, place `/assets/js/jquery.popup.min.js` in `/your/js/folder/`.

Add this just before your closing `body` tag, after you've included jQuery:

```html
<script src="/your/js/folder/jquery.popup.min.js"></script>
```

---

## Usage

Set up your html:

```html
<a href="https://ss2.bdstatic.com/70cFvnSh_Q1YnxGkpoWK1HF6hhy/it/u=756106789,206010103&fm=27&gp=0.jpg" class="popup">Popup link</a>
```

Call the plugin:

```javascript
var options = {};
$('a.popup').popup(options);
```

