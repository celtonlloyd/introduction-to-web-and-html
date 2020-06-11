# Introduction to the Web and HTML-CSS

## Web
A website works on the basis of the Client-Server model. Here, the website is stored on a server and the client makes a request to the server and are able to access the said website.  
The field of web development is divided into front-end and back-end with client being the front-end the server being the latter.

The client or the front-end is the user-facing side, where users interact with the websites or applications like your computers or mobiles or any internet accesible devices.
The languages or the technologies used for client-side programming are:
HTML
CSS
JavaScript.

Backend or the Server is a computer located somewhere in the world where the data for the websites are stored. Some of the languages used for server-side programming are : PHP, python, javascript(node.js).

## HTML-CSS
HTML is used to give structure to the website while CSS styles them and Javascript provides an interaction to them.

HTML is a markup language used to mark up the content within it like elements, tags and attributes.  
An example for a standard HTMl document would look like this

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Hello World</title>
  </head>
  <body>
  <h1>Hello World!</h1>
  </body>
</html>
```
The content displayed on the browser is nested within `<body></body>`.
Elements like `<h1></h1>`, `<p></p>`etc and self closing elements like `<br>, <hr>, <img>, <input>, <link>, <meta>` etc. are used within it.

CSS is used to define the visual styles and appearance of the HTML page.  
CSS can be referenced on the HTML file via 3 approaches:  Inline, Internal and external.  
Selectors like Type, Class and ID are used to relate the styles of the HTML elements to the CSS.  
  Properties and vaues are used to style those elements within the selectors.  
  An example for CSS would look like this
  ```
  body {
  background-color: green;
}
h1{
  color: black;
  font-size: 36px;
}
```
    
