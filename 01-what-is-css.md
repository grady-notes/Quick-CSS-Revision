# What is CSS ?

CSS stands for cascading style sheet. This is a language used for describing the visual looks & formatting of a document written in a markup langauge. The markup language does not necessarily have to be HTML it can be any other markup language.

CSS has also gone through different versions like HTML, only differene is that the versions are called levels. The table stating different versions is given below.

<table>
  <thead>
    <tr>
      <th>Version</th>
      <th>Year Of Inevention</th>
      <th>Key Features</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>CSS lvl 1</td>
      <td>1996</td>
      <td>Main font, border, color, alignment, positioning.</td>
    </tr>
    <tr>
      <td>CSS lvl 2</td>
      <td>Between 1997-2011</td>
      <td>
        absolute and fixed positioning, media types, z-order, pseudo classes
      </td>
    </tr>
    <tr>
      <td>CSS lvl 3</td>
      <td>2011 - current</td>
      <td>
        seperation into modules, media types, namespaces, lvl 3 selectors, lvl 3
        colors
      </td>
    </tr>
  </tbody>
</table>

CSS is composed by a set of rules applying style to elements matching a selector.

Each rule consists of a selector & a declaration block. The rule will be checked by the browser, and if applicablewill influence the part of the DOM targeted by the selector.
A selector is just a part that intensifies one or more elements where the declaration block must be applied. The declaration block consists of declarations surrounded by curly braces. Each declaration is a key-value pair composed of an english keyword that identifies the visual property that we want to change and the value we want to assign to that property.

For example if you want to change the font color of the body element, then the css would be

```css
body {
  color: red;
}
```

Here the "body" is the element seletor and the "color" is the key & "red" is the value for the specified key. The key-value is wrapped inside a set of curly brackets.

The rules cascade, hence the name cascading style sheet. They are applied in the order of prescedence like the many layers of an onion.

The order of prescedence is as given below

- Rules created by the browser
- Rules created by the user
- Rules created by the doument author

When an element is targeted by rules present in different layers, the outermost layer will take prescedence over the others.

Rules are also affected by inheritance. This is the mechanism by which properties are applied not only to the elements selected by the rule, but also to its descandants in the document hierarchy.
For example, if a font is applied to the body element of the document then the same font will be applied to all the text sensitive elements contained within the body element.
