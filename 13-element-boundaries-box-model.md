# Element Boundaries & CSS Box Model

# Element Boundaries

Each & every element in HTML is wrapped inside a default styling and indentation group. This group contains some properties known as padding, border & margin.

Their order of precedence is as follows.

<fieldset style="border: 1px solid red; color: red">
  Padding
  <fieldset style="border: 1px solid green; color: green">
    Border
    <fieldset style="border: 1px solid blue; color: blue">Margin</fieldset>
  </fieldset>
</fieldset>

Each property is explained in detail in the below table.

<table>
  <thead>
    <tr>
      <th>Property Name</th>
      <th>Description</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>Padding</td>
      <td>
        Allows us to change, edit or set a new padding are on all four sides of
        an element or on any individual side of an element
      </td>
    </tr>

<tr>
  <td>Border</td>
  <td>Allows us to change the default border applied onto an element.</td>
</tr>

<tr>
  <td>Margin</td>
  <td>Allows us to change the margin area on all four sides of an element.</td>
</tr>

  </tbody>
</table>

# CSS Box Model

The box model is the way that the browser calulates and figures out how to measure the space between two elements or the space taken by an individual element in the webpage.

Space taken by the browser for an element is the sum of the content area of the element & the space necessary for the padding & for the border.

The central area of the element is the space taken by the content of the element. Outside the central are there is a reserved space for the border & the padding, and if applied by the margin too.

Central area of the element is reduced in order to compute the padding or the border & the margin because the total area of the page remains the same & is locked by the device resolution.
