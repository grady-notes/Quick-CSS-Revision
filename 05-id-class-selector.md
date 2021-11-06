# ID & Class Selector

The ID & CLASS selector has specifically no description. This lesson is to just demonstrate how to select an element by ID or by their CLASS.
The element is selected by ID by using the "hash" symbol (#) & if the element is to be selected by a class, then the "dot" (.) must be used.

The below code gives an idea on how different elements can be selected on the basis of their ID & CLASS. I am using internal styling for this demonstration.

```html
<html>
  <head>
    <title>Some title</title>
    <style type="text/css">
      #homepage-header {
        background: yellow;
      }
      .grayed {
        color: white;
        background: gray;
      }
    </style>
  </head>

  <body>
    <header id="homepage-header">
      <img src="image path here" alt="any text" />
      <h1>Heading</h1>
    </header>
    <section>
      <p class="grayed">main paragraph</p>
    </section>
    <aside>Some sidebar here</aside>
    <footer>
      <div class="grayed">Footer info</div>
    </footer>
  </body>
</html>
```
