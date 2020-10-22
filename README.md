# DarkMode
MAKE YOUR WEBSITE CHANGE BETWEEN DARK MODE OR LIGHT MODE WITH LOCALSTORAGE

<br>

<p align="center">
    <a href="#usage">Usage</a> &bull;
    <a href="#get-start">Get Started</a> &bull;
    <a href="#license">License</a>
</p>

<br>
<br>

## USAGE
Install with `npm i @andreasrisager/darkmode`

<br>
<br>

## Get Started

##### *Javascript*
```javascript
import darkMode from "./node_modules/@andreasrisager/darkmode/index.js";

darkMode();
```

##### *HTML*
```html
<label class="theme-switch" for="darkmode">
    <input type="checkbox" id="darkmode">
    Dark Mode
</label>

<script type="module" src=""></script>
```

##### *CSS*
```css
[data-theme="dark"] {
    color: #e9e9e9;
    background-color: #1E1E1E;
}
```

<br>
<br>

## License
MIT
