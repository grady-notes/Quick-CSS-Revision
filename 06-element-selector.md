# Element Selector

An element selector is used to select the entire element for the styling purpose without having ot select a specific ID or a particular CLASS.

For example in this case,

```html
<html>
  <head>
    <title>Some title</title>
    <style type="text/css">
      footer {
        background: red;
        color: white;
      }
    </style>
  </head>

  <body>
    <header>
      <img src="https://placehold.it/100x100" alt="image here" />
      <h1>Heading</h1>
    </header>
    <section>
      <p>main paragraph</p>
    </section>
    <aside>Some sidebar here</aside>
    <footer class="main-footer">
      <div>Copyright© 2020</div>
    </footer>
  </body>
</html>
```

In this case the `<footer>` tag is directly styled without having to select the class.

**BUT THE MAIN DRAWBACK OF THE ELEMENT SELECTOR IS THAT THE STYLING WILL BE APPLIED TO ALL THE FOOTER ELEMENTS PRESENT INSIDE THE FOOTER, WHICH IS IN THIS CASE ARE THE `<div>` & `<p>` TAG.**
