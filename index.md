title: Web Development Tutorial
content-title: Blog on Web Development

### MarkDown Extensions & Favicon Utility:
- [Markdown Preview Enhancer](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [favicon Generator](https://favicon.io/)
---
### Web Development Tutorial

Welcome to this web development tutorial. In this guide, we will cover the basics of creating a simple web page using HTML, CSS, and JavaScript.

#### HTML

HTML (HyperText Markup Language) is the standard markup language for creating web pages. Here is a basic example of an HTML document:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Web Page</title>
</head>
<body>
    <h1>Welcome to My Web Page</h1>
    <p>This is a paragraph of text on my web page.</p>
</body>
</html>
```

#### CSS

CSS (Cascading Style Sheets) is used to style and layout web pages. Here is an example of how to add some basic styles to your HTML document:

```css
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 20px;
}

h1 {
    color: #333;
}

p {
    color: #666;
}
```

#### JavaScript

JavaScript is a programming language that allows you to create dynamic content on your web pages. Here is an example of a simple JavaScript function that changes the text of a paragraph when a button is clicked:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Example</title>
    <script>
        function changeText() {
            document.getElementById('myParagraph').innerText = 'Text has been changed!';
        }
    </script>
</head>
<body>
    <h1>JavaScript Example</h1>
    <p id="myParagraph">This is a paragraph of text.</p>
    <button onclick="changeText()">Change Text</button>
</body>
</html>
```

With these basics, you can start creating your own web pages. Happy coding!