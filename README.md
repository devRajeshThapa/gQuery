# gQuery

This is a lightweight utility library that provides a jQuery-like API. This library is designed to be easy to use and chainable, much like jQuery.

## Getting Started

### Installation

To use this, simply import the library into your JavaScript file.

```js
import $ from 'https://raw.githubusercontent.com/devrajeshthapa/gQuery/main/src/script.js';
```

### Example Usage

```js
import $ from 'https://raw.githubusercontent.com/devrajeshthapa/gQuery/main/src/script.js';

// Select an element and attach an event listener
$('#my-div').on('click', function() {
    alert('Div clicked!');
});
```

###  Methods

## `html(content)`
- **Description:** Get or set the innerHTML of the selected element.
- **Arguments:**
  - `content` (optional): The content to set as innerHTML.
- **Returns:** The innerHTML if no argument is provided, otherwise the object itself for chaining.

---

## `on(event, callback)`
- **Description:** Attach an event listener to the selected element.
- **Arguments:**
  - `event`: The event type (e.g., 'click', 'mouseover').
  - `callback`: The function to execute when the event is triggered.
- **Returns:** The object itself for chaining.

---

## `hide()`
- **Description:** Hides the selected element by setting its display property to none.
- **Returns:** The object itself for chaining.

---

## `show()`
- **Description:** Shows the selected element by setting its display property to block.
- **Returns:** The object itself for chaining.

---

## `attr(attributeName, value)`
- **Description:** Get or set an attribute of the selected element.
- **Arguments:**
  - `attributeName`: The name of the attribute.
  - `value` (optional): The value to set for the attribute.
- **Returns:** The value of the attribute if no value is provided, otherwise the object itself for chaining.

---

## `addClass(className)`
- **Description:** Adds a class to the selected element.
- **Arguments:**
  - `className`: The name of the class to add.
- **Returns:** The object itself for chaining.

---

## `removeClass(className)`
- **Description:** Removes a class from the selected element.
- **Arguments:**
  - `className`: The name of the class to remove.
- **Returns:** The object itself for chaining.

---

## `toggleClass(className)`
- **Description:** Toggles a class on the selected element.
- **Arguments:**
  - `className`: The name of the class to toggle.
- **Returns:** The object itself for chaining.

---

## `css(property, value)`
- **Description:** Get or set a CSS property of the selected element.
- **Arguments:**
  - `property`: The CSS property name (e.g., 'color', 'background-color').
  - `value` (optional): The value to set for the CSS property.
- **Returns:** The value of the CSS property if no value is provided, otherwise the object itself for chaining.

---

## `getWidth()`
- **Description:** Get the width of the selected element (including padding and borders).
- **Returns:** The width of the element in pixels.

---

## `getHeight()`
- **Description:** Get the height of the selected element (including padding and borders).
- **Returns:** The height of the element in pixels.

---

## `width(value)`
- **Description:** Get or set the width of the selected element.
- **Arguments:**
  - `value` (optional): The width value in pixels to set.
- **Returns:** The width of the element in pixels if no value is provided, otherwise the object itself for chaining.

---

## `height(value)`
- **Description:** Get or set the height of the selected element.
- **Arguments:**
  - `value` (optional): The height value in pixels to set.
- **Returns:** The height of the element in pixels if no value is provided, otherwise the object itself for chaining.
```

Feel free to modify any sections as needed!
