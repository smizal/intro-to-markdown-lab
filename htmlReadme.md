# How to write an HTML Boilerplate

![HTML Boilerplate](https://1.bp.blogspot.com/-AN8ymYdeue8/YUuGiZrOvKI/AAAAAAAACEc/V1YUmIjfx0IgaiWzZH_LPjOIkwIu2w2ZQCLcBGAsYHQ/w640-h334/boilerplate2.png)

## What is an HTML 5 boilerplate?

A boilerplate in HTML is **a template you will add at the start of your project**. You should add this boilerplate to all of your HTML pages. It is the basic foundation for the page.

## Main HTML 5 boilerplate

Look at the following example that shows the main elements of HTML 5 boilerplate

```
<!DOCTYPE html>
<html>
  <head>
    ...
  </head>
  <body>
    ...
  </body>
</html>
```

### **1- What is a doctype in HTML?**

The first line in your HTML code should be the doctype declaration `<!DOCTYPE html>`. A doctype tells the browser what version of HTML the page is written in.

If you forget to include this line of code in your file, then some of the HTML 5 tags like `<article>`, `<footer>`, and `<header>` may not be supported by the browser.

---

### **2- The html element**

The `<html>` tag is the top level element of the HTML file. You will nest the `<head>` and `<body>` tags inside of it.

We can add `lang` attribute inside it. e.g `<html lang="en">` to define the language used in the page.

---

### **3- The head element/tags**

The `<head>` tags contain information that is processed by machines/browsers. Inside the `<head>` tags, you will nest metadata which is data that describes the document to the machine, links/reference to other files like _CSS_ and _javascript_ of _fonts_ files.

_**Examples in metadata and links:**_
There are many examples and meta tags we can include in the `head` _**including, But Not Limited To**_:

- **Character encoding:** UTF-8 is the standard character encoding you should use in your web pages.

```
<meta charset="UTF-8">
```

---

- **Viewport**: This tag renders the width of the page to the width of the device's screen size. If you have a mobile device that is 600px wide, then the browser window will also be 600px wide. The initial-scale controls the zoom level. The value of 1 for the initial-scale prevents the default zoom by browsers.

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

- **title tag:** The _title_ tag is the title for the web page. This text is shown in the browser's title bar.

```
<title>HTML 5 Boilerplate</title>
```

---

- **CSS stylesheet link:** This code will link your custom CSS to the HTML page. _`rel="stylesheet"`_ defines the relationship between the HTML file and the external stylesheet.

```
<link rel="stylesheet" href="style.css">
```

---

- **Script tag:**
  External script tags will be placed just before the ending body tag. This is where you can link your external JavaScript code. or you can place within the head elements with a _`defer`_ to make the browser loads all the page elements then read the javascript file.

```
<script defer src="index.js"></script>
```

---

### **3- The body element**

The visible part of the HTML document is between `<body>` and `</body>`.

It will hold all and every elements that will be shown in the browser.

---

You can read more and th learn beginners' HTML in [W3Schools](https://www.w3schools.com/html/default.asp)
