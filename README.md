# Build a Website: Tasks

1. Create a Webpage with Your name, some color, and an image.
2. Add two buttons to the webpage, named some colors (e.g. red, blue)
3. Use Javascript to change the color on your page, using the buttons

## Instructions

- Find a browser to use (Chrome, Edge, FireFox, Safari, etc.)
- Find a "Text Editor" to use (for now, https://codepen.io/pen/ is easy because you don't have to install anything).
- Use the resources below to figure out html basics, and then start adding html inside your text editor
- Download an image and make sure your img src points to the file location, e.g. `<img src="c:\\users\\me\\Downloads\\volleyball.jpg" >`
- When you get to task 3, use the `onclick` attribute of a button to modify your colors 

### Resources:

https://www.w3schools.com/html/html_basic.asp

https://www.w3schools.com/html/html_colors.asp

https://www.w3schools.com/html/html_images.asp

https://www.w3schools.com/jsref/event_onclick.asp

https://www.w3schools.com/js/js_htmldom_css.asp

### Example Output
```<!DOCTYPE html>
<html>
<body id="b" style="background-color: red">

<h1>Grant</h1>
<p style="color:white">This is my example website</p>
<img src="https://cdn11.bigcommerce.com/s-2sxhiat0li/images/stencil/1280x1280/products/178/1159/V5M5000-3N_AD__42614.1559605550.jpg?c=2&imbypass=on" alt="Mission img not available" height=300 >
<button onclick="document.getElementById('b').style.background='Purple'"> Purple </button> 
<button onclick="document.getElementById('b').style.background='Blue'"> Blue </button> 

</body>
</html>
```




#### AJ's code:
<!DOCTYPE html>
<html>will both buttons?
<body id="b" style="background-color:DodgerBlue;">
  <h1>will you to</h1>
<img src="https://res.cloudinary.com/dk-find-out/image/upload/q_80,w_1920,f_auto/Mosasaurus_00824573_dhgg11.jpg" height=200 alt="The Strongest being">
<p style="color:MediumSeaGreen;">
<p>The Mosasaurus</p>
<button onclick="document.getElementById('b').style.background='Blue'">This button does nothing!</button>
Will you click both buttons???
  </body>
</html>
<button onclick="document.getElementById('b').style.background='Red'">This button does nothing2!</button>
