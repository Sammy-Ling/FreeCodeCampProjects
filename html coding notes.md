# FreeCodeCampProjects
 Learning Code Basics

# Responsive Web Design Certification Notes

## HTML Basics 

* Html elements have opening and closing tags e.g opens with `<h1>` and closes with `</h1>`

* H elements go from h1 to h6, indicating important such that h1 is more important than h6

* P element is to create a paragraph

* To add comments in html, use 
```html
<!-- and -->
```

* You can create different content areas, such as `<main> </main>`. Elements nested inside another element are usually indented with two spaces to show they are nested.



## Images and Links

* You can add images with the `<img>` tag, which does NOT have a closing tag

* You can use `<img src=...>` this will specify the location of the image, usually a url

* It is always good practice to add an  `alt="..."` attribute to images, just in case the image does not load

* You can link to another page using the `<a>` element along with `href="..."`, e.g `<a href='https://hello123.com'></a>`

* You can also add a link between the anchor element `<a>` and the closing tag for `</a>`

* If you want to turn a text into a link, add a href to the element and close them in `<a>` tags e.g
    ```html
    <p>See more <a href="https://freecatphotoapp.com">cat photo </a>in our gallery.</p>
    ```
 

* You can add `target="_blank"` so that the link opens in a new tag



## Formatting and Sections

* `<section> </section>` to create a new section

* You can add lists using the `<ul>` element, then using `<li></li>` elements within the `<ul>` element

* `<figure>` element allows you to nest images with a caption and after an image, using `<figcaption>` allows you to put a caption to an image

* You can also use `<em></em>` to nest words you want to emphasise and you can use `<strong></strong>` to make the words bold

* Using `<ol>` you create a list that has an order to the items, make sure to still use <li> for the elements nested inside the ordered list

* `<form>`` creates a webform to collect information, make sure to add 'action' right after form to set a path such as 
```html 
<form action="https....">
```
* `<input>` element is another way to collect data from a form
* `<legend>` adds a caption to a fieldset

- adding 'type' to any input allows you to create different attributes such as passwords or buttons etc
- adding 'name' assigns a value which represents the data you are gathering, by giving radio the same name it will  deselect other answers, when one is selected
- adding 'placeholder' gives users a hint to what you want them to input
- adding 'required' means that a user must give an answer or response before being able to submit data
- adding type="radio" to an input allows for users to answer one out of many options
- adding an id attribute is essential for identifying the HTML elements, it must be unique
- adding 'value' specifies the value you want to send to the backend
- You can also input a checkbox attitribute for multiple answer selections
adding for after the input e.g input `for="..."` allows you to associate the answer to certain value sent to server side

* Nesting into a `<label>` element helps associate thetext for input element with the input itself
adding a submit element at the end allows users to click and send the data you want, by default going to form action address
* You can add a textarea element to receive answers for a form with multiple lines of answer, using 'rows' and 'cols' attribute for the textarea for sizing
* Placeholder attribute for the textarea gives the user a chance to see an example answer for the textarea in question

Adding the link attritube allows you to link to exteneral stylesheet or css sheets

* `<form action="https://register-demo.freecodecamp.org" method="post"></form>` allows you to send the information gathered to the link provided, method is the way in which you want to send the form data

## Styling

* `vh`` stands for viewport height
* `'body' margin:0` makes no space between edge and text
* `'body' background-color:x` changes the background colour to x
* `'body'` color changes the text in the body

## Paintings

* `<div class="canvas"></div>` this sets a canvas for painting 
 - dont forget <link href> to set your CSS!
* `<div class="frame">` for framing a canvas/painting
* `css styling 'overflow:hidden'` returns the size you orignally had
* css sizes dont have to be just pixels (`px`), can be percentages e.g 25%
* `css styling 'filter:blur(2px)'` adds a blur to the painting/canvas
* `css styling 'box-shadow'` adds a shadow to edges to make them look more realistic
* `css styling 'border-radius'` allows you to smooth the edges, rounding them off
* `css styling 'transform:rotate(0.Xdeg)'` allows you to rotate to x degress, - for anticlockwise
* `css styling 'box-sizing:content-box'` shrinks borders to accomodate content size, 'border-box' does the opposite
* `css styling 'font-family'` changes the font style 
* `css styling 'text-transform'` can be used to set capitals by setting it to 'uppercase'

## CSS styling flexbox
* `'display:flex'`
    - `flex-direction` allows you to change the spacing of images e.g 'row' puts them left to right
    - `flex-wrap` allows for items to either shrink to fit into the boxes you created or extend outwards with nowrap
    - `align-items` allows you to align them within box
    - `object-fit` will tell the size the image to the container/box. use 'cover' to align perfectly
    - `gap`` adds a gap to the borders







