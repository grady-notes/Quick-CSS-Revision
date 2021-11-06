# Attribute Selector

Elements in the HTML can be styled without having to select an ID or a CLASS by directly selecting the entire element. There is one more useful way of styling such cases by selecting the attribute of the desired element. Doing so can help us style elements of the similar type having different attribute.

For example,

```html
<html>
  <head>
    <title>Some title</title>
    <style type="text/css">
      input[type="text"] {
        background: red;
      }
      input[type="password"] {
        background: green;
      }
      input[type="submit"] {
        background: blue;
        color: white;
      }
    </style>
  </head>

  <body>
    <form>
      <fieldset>
        <br />
        Username - <input type="text" name="username" /><br /><br />
        Password - <input type="password" name="password" /><br /><br />
        <input type="submit" name="login-button" value="Login" />
      </fieldset>
    </form>
  </body>
</html>
```
