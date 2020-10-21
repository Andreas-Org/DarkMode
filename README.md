# DarkMode
USE THIS SUPER AWESOME AND EPIC DARK THEME SO YOU CAN MAKE YOUR WEBSITE CHANGE BETWEEN LIGHT MODE OR DARK MODE

## USAGE
Install with `npm i @andreasrisager/darkmode`

###### Javascript
```javascript
var darkMode = require("@andreasrisager/darkmode");

darkMode();
```

###### HTML
```html
<label class="theme-switch" for="darkmode">
    <input type="checkbox" id="darkmode">
    Dark Mode
</label>
```

###### CSS
```css
[data-theme="dark"] {
    color: #e9e9e9;
    background-color: #1E1E1E;
}
```