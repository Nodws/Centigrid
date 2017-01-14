# Centigrid
Centigrid is a straightforward  grid system based on flexbox and percentages that leaves the styling to you the designer.

## Install
Just include the file before your main styles

    `<link href="assets/css/centigrid.css" rel="stylesheet">`
    
## The grid
Grid is based on a 100% width, so col1 will be 10%, col2 20%, and so on until col10 (full width)

## Styling 
That's the best part! Centigrid doesn't mess with your poppies 

## Example
http://codepen.io/nodws/pen/vyJEoX

### Markup
```html
<div class="centigrid">
    <div class="col4 middle">
      <img src="https://placeimg.com/440/480/animals">
    </div>
    <div class="col4 text-justify">
      <h2>A Book Title</h2>
      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It</p>
 </div>
    <div class="col2 middle center">
      <a href="#" class="button"> BUY NOW </a>
    </div>
  </div>
```
