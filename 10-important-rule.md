# Important Rule

The important rule always wins over any other declaration affecting the same element even if the other specific rules are present. This rule should only be used in emergency situations and is not for casual styling purposes. It an be used to override 3rd party stylesheets such as bootstrap or ui-kit.

An example of the important rule is given as follows,

```html
<head>
  <style>
    section.posts article.first a {
      color: red;
    }
    a {
      color: green !important;
    }
  </style>
</head>
<section class="posts">
  <article class="first">
    <p>Hello, read <a>more</a></p>
    .
  </article>
</section>
```

Now, even though the first declaration is more specific, the color of the anchor will be green & that is because of the !important rule.

**THE IMPORTANT RULE CANNOT BE APPLIED TO A BLOCK. IT SHOULD BE APPLIED INDIVIDUALLY TO EACH DECLARATION THAT IS TO BE CHANGED.**
