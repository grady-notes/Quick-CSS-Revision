# Specificity Rule & Tree Proximity Ignorance

## The specificity rule

The specificity rule is a group of four distinct numbers spereated by a comma which are used to determine which rule to apply when multiple rules match the same element.

It starts at 0,0,0,0 with the most important value at the extremem left and the least important value at the extreme right. For 0,0,1,0 carries more significance than 0,0,0,10 & similarly 0,1,0,0 carries more significance than 0,0,10,20

0,0,0,0 when named form left ro right as A,B,C,D respectively the browser calculates the specificity as folows.

## Column A is incremented on inline styles.

```
<div style="selector: style">
```

## Column B is incremented for each ID selector

```
#id{style}
```

## Column C is incremented for each CLASS selector or pseudo class selector or attribute selector

```
.class{style}, element:hoover{style}, element[type]{style}
```

## Column D is incremented for each element selector

```
body{style}
```

# Tree Proximity Ignorance

CSS engines are not sensitive to element proximity when computing CSS rule specificity. It means that if you have two or more rules targetting the same element very similarin nature & with the same exact specificity, the one that will win is the last one passed by your browser even if the element indicated in the first rule is more closely related. Thats because the specificity value doesnt take into account a location factor & then having the same exact specificity, the winner is simply who comes last. This is due to the fact that the CSS works like an onion skin.

<fieldset style="color: red; border: 2px solid red">
  Third CSS file
  <fieldset style="color: green; border: 2px solid green">
    Second CSS file
    <fieldset style="color: blue; border: 2px solid blue">
      First CSS file.
    </fieldset>
  </fieldset>
</fieldset>

Example

```html
<head>
  <style>
    div {
      color: red;
    }
    section a {
      color: blue;
    }
  </style>
</head>
<section>
  <div>
    <a>TEST</a>
  </div>
</section>
```

In the example the text will be blue and not red due to the tree proximity ignorance.
