# HTML Crash Course

![HTML Logo](/images/html.png)

## What is HTML?

HTML, which stands for `Hyper Text Markup Language`, is one of the three fundamental web development languages (the other two being CSS and JavaScript). HTML is a markup language, which means it's job is to provide the pieces of your website. Websites just built with HTML don't contain any style or refined layout (provided by CSS) or functionality (provided by JavaScript), but they do contain all the pieces the website needs, and they would be laid out in a semi-organized structure.

Imagine your website is a car. HTML would be the pieces of that car, such as the tires, windows, seats, and more. CSS would tell those pieces where to be and what they look like, such as paint color, how big the tires are, and interior color. JavaScript would provide the action of the car, such as what the car is supposed to do when you press the gas or brake pedals.

All three languages are important to building a website!

## HTML tag & element syntax

The pieces of a website in HTML are called `elements`. Elements are wrapped in `tags` so you can more easily define where an element is supposed to start and stop. Opening tag syntax looks like `<element>`, while closing tag syntax looks like `</element>`. Some elements don't need to contain content in between them, so we can self close them like `<element />`. These are called `Void tags`.

```html
<!-- Element with opening and closing tags -->
<p>I am a paragraph element!</p>

<!-- Element with a void tag -->
<input />
```

## Creating and setting up an HTMl file

To start writing HTML, create a file that ends with the `.html` extension (`index.html` is a common name for the main HTML file in a website). To set up an HTML file we need to do some set up, it will look something like this:

```html
<!DOCTYPE html>
<html>
  <head></head>
  <body></body>
</html>
```

`!DOCTYPE` is not an HTML tag, but rather lets the browser know what type of file this is, and what version of HTML we are using (html just defaults to the most recent stable version).

The `html` element is used to wrap all of our HTML code.

The `head` element contains information about the website (`meta` elements mostly)

The `body` element contains the elements that make up the user interface of the website, or what the user will actually see.

## Know your elements!

Get familiar with what elements are available to you here: https://developer.mozilla.org/en-US/docs/Web/HTML/Element