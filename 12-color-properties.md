# Color Properties

## color

Allows us to change the color of the desired block. Possible values can be a predefined keyword, currentcolor(for applying the color of the parent element), an rgb component value, rgb added with alpha value to add transparency to the text & a hexadecimal code.
For example,

```html
<head>
  <style>
    div {
      color: red;
    }
  </style>
</head>
<body>
  <div>this is a div with red text.</div>
</body>
```

## background-color

Allows us to change the background color of the desired section of the webpage. Possible values are same as the preious property.
For example,

```html
<head>
  <style>
    div {
      background-color: red;
    }
  </style>
</head>
<body>
  <div>this is a div with red background.</div>
</body>
```

## background-image

Very similar to the previous property, the bakground image property allows us to not only change the color, but it also allows us to change the image that is being used in the background of an element. Possible value is url. Inside the url attribute, full path of the image should be mentioned.
For example,

```html
<head>
  <style>
    p {
      height: 500px;
      background-image: "image path here";
    }
  </style>
</head>
<body>
  <p>
    lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
    cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
    non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
  </p>
</body>
```
