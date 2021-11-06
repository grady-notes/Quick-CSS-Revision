# Text & Font Properties

Some of the very basic properties of CSS that are used to determine how the text on a webpage is rendered are as follows

## font-family

Specifies what font is to be used throughout the webpage or on a desired portion of the webpage. Can be one single font name or multiple names seperated by commas.

```html
<head>
  <style>
    div p {
      font-family: serif;
    }
  </style>
</head>
<div>
  <p>This is an example of font-family serif</p>
</div>
```

```html
<head>
  <style>
    div p {
      font-family: sans-serif;
    }
  </style>
</head>
<div>
  <p>This is an example of font-family sans-serif</p>
</div>
```

## font-size

Specifies the size of the displayed text on the webpage. Possible values can be inherit, xx-small, x-small, small, large, x-large, xx-large, smaller, larger, length(px), percentage.

```html
<head>
  <style>
    div p {
      font-size: 50px;
    }
  </style>
</head>
<div>
  <p>This is an example of font-size in length(px)</p>
</div>
```

## font-weight

Allows the user to determine the boldness of the font. Possible values are normal, bold, range (ex. 100-400 is considered normal, 500-700 is considered as bold, 800-900 is considered as bolder & above 900 is considered as extra bolder which may not be supported by current browsers.)

```html
<head>
  <style>
    div p {
      font-weight: 800;
    }
  </style>
</head>
<div>
  <p>This is an example of font-wight in range</p>
</div>
```

## font-style

Determines the way the font is rendered on the webpage i.e. it is used to instruct the browser to render the font in bold or italic. Possible values are bold, italic, oblique, inherit.

```html
<head>
  <style>
    div p {
      font-style: italic;
    }
  </style>
</head>
<div>
  <p>This is an example of font-style in italic</p>
</div>
```

## line-height

Used to determine the tallness of each line of text that is displyed throughout the webpage. Possible values are inherit, normal, length, percentage.

```html
<head>
  <style>
    div p {
      line-height: 3;
    }
  </style>
</head>
<div>
  <p>This is an example of line-height in length</p>
</div>
```

## letter-spacing

This property lets us change the space between the letters in the text. Possible values can be inherit, length(px), percentage.

```html
<head>
  <style>
    div p {
      letter-spacing: 5px;
    }
  </style>
</head>
<div>
  <p>This is an example of letter-spacing in px</p>
</div>
```

## word-spacing

Similar to letter-spacing, word spacing is used to change & adjust the space between two words in a webpage. Possible values are inherit, normal, length(px), percentage.

```html
<head>
  <style>
    div p {
      word-spacing: 5px;
    }
  </style>
</head>
<div>
  <p>This is an example of word-spacing in px</p>
</div>
```

## text-align

Allows us to change the default alignment of the text the is contained within the webpage or in a desired section of webpage. Possible values are left, right, center.

```html
<head>
  <style>
    div p {
      text-align: center;
    }
  </style>
</head>
<div>
  <p>This is an example of center aligned text</p>
</div>
```

## text-indent

Allows us to hange the default indentation of the the text in a paragraph or any desired section of the webpage. Possible values are length(px), percentage.

```html
<head>
  <style>
    div p {
      text-indent: 50px;
    }
  </style>
</head>
<div>
  <p>This is an example of text-indent in px</p>
</div>
```

## text-transform

Allows us to transform the default casing of the text i.e. uppercase, lowerase, etc. Possible values are uppercase, lowercase, capitalize.

```html
<head>
  <style>
    div p {
      text-transform: uppercase;
    }
  </style>
</head>
<div>
  <p>This is an example of uppercase transformed text</p>
</div>
```

## text-decoration

Allows us to edit and/or control the way the text is rendered on the webpage. Possible values are underline, overline, line-through, none.

```html
<head>
  <style>
    div p {
      text-decoration: line-through;
    }
  </style>
</head>
<div>
  <p>This is an example of line-through decoration</p>
</div>
```
