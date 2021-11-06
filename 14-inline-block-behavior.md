# How Inline & Block Level Elements Deal With Dimensions

Somethings are very important about the block level & inline elements from the information point of view. They are listed below.

## Inline Elements.

- Flow along the content of the page.
- Dont cause line breaks before or after the content they wrap.
- Ignore top & bottom margins, but will consider left & right ones along with the padding.
- Ignore width & height properties.
- Consider vertical alignment.

## Block Level Elements.

- Expand to fit the maximum horizontal space of their parent element.
- Cause line breaks before & after the content they wrap.
- Can have margins/paddings or both together.
- If no width is set, they naturally expand to fit their parents.
- Ignore vertical alignment.
