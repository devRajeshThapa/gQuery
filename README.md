# gQuery

This is a lightweight utility library that provides a jQuery-like API. This library is designed to be easy to use and chainable, much like jQuery.

## Installation

To use this, simply import the library into your JavaScript file.

```js
import $ from 'https://raw.githubusercontent.com/devrajeshthapa/gQuery/main/src/script.js';
```

## Example Usage

```js
import $ from 'https://raw.githubusercontent.com/devrajeshthapa/gQuery/main/src/script.js';

// Select an element
const myDiv = $('#my-div');

// Set HTML content
myDiv.html('<p>Hello, world!</p>');

// Add a class
myDiv.addClass('my-class');

// Set CSS properties
myDiv.css('color', 'red');

// Attach an event listener
myDiv.on('click', function() {
    alert('Div clicked!');
});

// Hide the element
myDiv.hide();

// Show the element
myDiv.show();
```
