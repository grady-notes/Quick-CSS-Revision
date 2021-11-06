# Inline, Internal & External CSS

There are 3 ways to include CSS in a markup file:

## Inline Styling

Inline styling is a type of styling the HTML document by directly writing the style code into the element.
For example,

```html
<body>
  <p style="font-size: 50px;">Hello</p>
</body>
```

## Internal Styling

Internal Styling is another way to style an HTML document by opening a style tag within the head tag.
For example,

```html
<head>
  <style type="text/css">
    p {
      font-style: 50px;
      color: blue;
    }
  </style>
</head>
<body>
  <p>Hello</p>
</body>
```

## External Styling

External styling is the most efficient & the most flexible way to style an HTML document. It means that an external css file which has to be linked in the HTML document with the help of the `<link>` tag. The `<link>` tag does not have a closing tag.
For example,

### index.html

```html
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="path to css" />
  </head>
  <body>
    <p>Hello</p>
  </body>
</html>
```

### style.css

```css
p {
  font-size: 50px;
  color: green;
  text-decoration: underline;
}
```
