# DarkMode
USE THIS SUPER AWESOME AND EPIC DARK THEME SO YOU CAN MAKE YOUR WEBSITE CHANGE BETWEEN WHITE MODE OR DARK MODE

## USAGE
Install with `npm i @andreasrisager/darkmode`

```javascript
var darkMode = require("@andreasrisager/darkmode");

darkMode();
```

```html
<label class="theme-switch" for="darkmode">
    <input type="checkbox" id="darkmode">
    Dark Mode
</label>
```

```css
[data-theme="dark"] {
    color: #e9e9e9;
    background-color: #1E1E1E;
}
```