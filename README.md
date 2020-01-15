# Scroll to class 
This vertical scroll code was done in pure javascript

## Repository
This repository contains a example of the vertical scroll funtion, only is necesary to clone the repository and run index.html 

## Include to your project
Only is necesary to copy the scroll.js file into your project and include the scroll.js in your html or javascript file

##### HTML
```html
<script type="text/javascript" src='./scroll.js'></script>
```
##### Javascript
```javascript
include './scroll.js';
```
## Usage
To usage you have to add in the href attribute of the link (tag: a), the class name of the element that you want to point and assign the function to the link
```html
<a id='home_link' href='#home'></a>
```
```javascript
const element = document.getElementById('home_link');
element.onclick = (e) => 
{
    e.preventDefault();
    scrollTo('home');
}
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
