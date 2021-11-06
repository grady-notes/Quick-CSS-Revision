# CSS Properties & Measures

Since there are very few properties in CSS, they can be classified into 4 categories,

- Text/Font properties
- Color properties
- Dimensional properties
- Display & positioning properties

Many of the css properties we see, define a measurable quantity like the font size or the border size. So its fundamental to know which unit of measure css uses to express those values.

The most widely used measures are given in the below table.

<table>
  <thead>
    <tr>
      <th>Unit</th>
      <th>Symbol</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Perentage</td>
      <td>%</td>
      <td>
        Expressed as a percentage value in relation to the containing element,
        for example 50% width means that 50% of the horizontal space is reserved
        from the total available spae in the containing element.
      </td>
    </tr>
    <tr>
      <td>Pixels</td>
      <td>px</td>
      <td>
        Fixed size units. One pixel(px) means one doton your device screen. They
        are always uniform across the webpage.
      </td>
    </tr>
    <tr>
      <td>EM unit</td>
      <td>em</td>
      <td>
        Scalable unit. It expresses the size of an element by computing it in
        relation to the width of the uppercase 'M' in the current font of the
        web page.
      </td>
    </tr>
    <tr>
      <td>Root EM unit</td>
      <td>rem</td>
      <td>
        Introduced in CSS-3, the rem unit is a scalable unit that expresses the
        size of an element in relation to the width of the uppercase 'M' used on
        the root mode in the current font.
      </td>
    </tr>
  </tbody>
</table>
