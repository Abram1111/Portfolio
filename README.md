# Bootstrap Components Documentation

This document provides an in-depth breakdown of how Bootstrap components are used in the portfolio website.

## Navbar

### Navbar Container
```html
<nav class="navbar navbar-expand-lg fixed-top ">
```
#### Explanation:
- `navbar`: Defines a responsive navigation bar.
- `navbar-expand-lg`: Expands the navbar on large screens (≥992px).
- `fixed-top`: Fixes the navbar to the top of the viewport.


### Toggler Button
```html
<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
```
#### Explanation:
- `navbar-toggler`: Creates a button that toggles the menu.
- `data-bs-toggle="collapse"`: Enables collapsing functionality.
- `data-bs-target="#navbarNav"`: Targets the collapsible menu container.

## Hero Section

### Container Layout
```html
<section id="home" class="vh-100 d-flex align-items-center justify-content-center text-center">
```
#### Explanation:
- `vh-100`: Sets the section height to 100% of the viewport height.
- `d-flex`: Enables Flexbox layout.
- `align-items-center`: Vertically centers the content.
- `justify-content-center`: Horizontally centers the content.
- `text-center`: Aligns text to the center.

## About Section

### Container Layout
```html
<section id="about" class="py-5 d-flex align-items-center">
```
#### Explanation:
- `py-5`: Adds vertical padding.
- `d-flex`: Enables Flexbox layout.
- `align-items-center`: Vertically centers content.

### Profile Image
```html
<div class="pic p-2 rounded-circle border border-5">
```
#### Explanation:
- `p-2`: Adds padding.
- `rounded-circle`: Makes the image circular.
- `border`: Adds a border.
- `border-5`: Sets the border width to 5 units.

## Projects Section

### Project Cards
```html
<div class="card text-center h-100 overflow-hidden">
```
#### Explanation:
- `card`: Defines a card layout.
- `text-center`: Centers text inside the card.
- `h-100`: Sets the card height to 100% of its container.
- `overflow-hidden`: Hides content that overflows the card boundaries.

### Project Button
```html
<a href="#" class="btn">View Project</a>
```
#### Explanation:
- `btn`: Applies button styling.

## Contact Section

### Form Controls
```html
<input type="text" class="form-control" required>
```
#### Explanation:
- `form-control`: Provides consistent styling for form elements.
- `required`: Marks the field as mandatory.

### Submit Button
```html
<button type="submit" class="btn">Submit</button>
```
#### Explanation:
- `btn`: Applies button styling.

## Footer

### Social Media Icons
```html
<a href="#" class="text-white mx-2" data-bs-toggle="tooltip" title="LinkedIn">
<i class="fab fa-linkedin"></i>
```
#### Explanation:
- `text-white`: Sets the text color to white.
- `mx-2`: Adds horizontal margin.
- `data-bs-toggle="tooltip"`: Activates Bootstrap tooltips.
- `fab fa-linkedin`: Displays the LinkedIn icon from Font Awesome.

This README file provides a comprehensive guide to how Bootstrap classes are applied to design and structure the portfolio website.

