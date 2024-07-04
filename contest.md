### HTML Lists

1. **Which HTML tag is used to define an unordered list?**
   - A. `<ul>` 
   - B. `<ol>` 
   - C. `<li>` 
   - D. `<list>`
   - **Correct Answer: A. `<ul>`**
   - **Explanation:** `<ul>` stands for unordered list, which is a list of items marked with bullets.

2. **Which attribute is used to specify the type of marker in an ordered list?**
   - A. `type`
   - B. `marker`
   - C. `style`
   - D. `list-type`
   - **Correct Answer: A. `type`**
   - **Explanation:** The `type` attribute specifies the kind of marker (number, letter, etc.) to use in an ordered list (`<ol>`).

### HTML Tables

3. **Which HTML tag is used to define a table header?**
   - A. `<thead>` 
   - B. `<th>` 
   - C. `<head>` 
   - D. `<header>`
   - **Correct Answer: B. `<th>`**
   - **Explanation:** `<th>` stands for table header and is used to define header cells in a table.

4. **Which attribute is used to merge two or more table cells horizontally?**
   - A. `colspan`
   - B. `rowspan`
   - C. `merge`
   - D. `span`
   - **Correct Answer: A. `colspan`**
   - **Explanation:** The `colspan` attribute specifies the number of columns a cell should span.

### HTML Basic Tags

5. **Which HTML tag is used to create a hyperlink?**
   - A. `<link>` 
   - B. `<a>` 
   - C. `<href>` 
   - D. `<url>`
   - **Correct Answer: B. `<a>`**
   - **Explanation:** The `<a>` tag is used to define a hyperlink.

6. **What is the correct HTML tag for inserting a line break?**
   - A. `<br>` 
   - B. `<lb>` 
   - C. `<break>` 
   - D. `<newline>`
   - **Correct Answer: A. `<br>`**
   - **Explanation:** The `<br>` tag is used to insert a line break in HTML.

### Inline Block Elements

7. **Which of the following is an inline element?**
   - A. `<div>`
   - B. `<p>`
   - C. `<span>`
   - D. `<section>`
   - **Correct Answer: C. `<span>`**
   - **Explanation:** `<span>` is an inline element used to apply styles or behaviors to a small part of text.

8. **Which CSS property can be used to make a block element behave like an inline element?**
   - A. `display: block;`
   - B. `display: inline;`
   - C. `display: flex;`
   - D. `display: grid;`
   - **Correct Answer: B. `display: inline;`**
   - **Explanation:** The `display: inline;` property changes the display behavior of an element to inline.

### CSS Flexbox

9. **Which CSS property is used to define a flex container?**
   - A. `display: block;`
   - B. `display: inline;`
   - C. `display: flex;`
   - D. `display: grid;`
   - **Correct Answer: C. `display: flex;`**
   - **Explanation:** The `display: flex;` property makes an element a flex container, enabling flexbox layout.
 
 Sure! Here are 10 multiple-choice questions on various CSS concepts including CSS Grid, CSS Flexbox, CSS inheritance, CSS specificity, CSS Box Model, and CSS selectors:

### 10. CSS Grid
**Question:** Which CSS property and value combination will create a 3-column layout in CSS Grid?

```css
.container {
  display: grid;
  __________;
}
```
**Options:**
a) `grid-template-columns: 1fr 1fr 1fr;`  
b) `grid-template-columns: auto auto auto;`  
c) `grid-columns: 1fr 1fr 1fr;`  
d) `columns: 3;`

**Correct Answer:** a) `grid-template-columns: 1fr 1fr 1fr;`

**Explanation:** The `grid-template-columns` property defines the number of columns in a grid layout. The value `1fr 1fr 1fr` creates three columns of equal width.

### 11. CSS Flexbox
**Question:** How do you center an item horizontally and vertically within a flex container?

```css
.container {
  display: flex;
  __________;
}
.item {
  __________;
}
```
**Options:**
a) `justify-content: center; align-items: center;`  
b) `justify-content: center; align-content: center;`  
c) `align-items: center; align-content: center;`  
d) `justify-content: center; align-self: center;`

**Correct Answer:** a) `justify-content: center; align-items: center;`

**Explanation:** `justify-content: center` centers the item horizontally and `align-items: center` centers it vertically within the flex container.

### 12. CSS Inheritance
**Question:** Which CSS property is not inherited by default?

**Options:**
a) `color`  
b) `font-size`  
c) `border`  
d) `line-height`

**Correct Answer:** c) `border`

**Explanation:** The `border` property is not inherited by default, whereas properties like `color`, `font-size`, and `line-height` are inherited.

### 13. CSS Specificity
**Question:** Which of the following selectors has the highest specificity?

**Options:**
a) `.class`  
b) `#id`  
c) `element`  
d) `element.class`

**Correct Answer:** b) `#id`

**Explanation:** ID selectors have a higher specificity compared to class selectors, type selectors, and combined selectors.

### 14. CSS Box Model
**Question:** Which property would you use to add space inside an element, but outside its content area?

**Options:**
a) `margin`  
b) `padding`  
c) `border`  
d) `width`

**Correct Answer:** b) `padding`

**Explanation:** The `padding` property adds space inside an element, between the content and the border.

### 15. CSS Selectors
**Question:** How would you select all `<a>` elements inside a `<div>` with the class `.menu`?

```css
__________ {
  color: red;
}
```
**Options:**
a) `div .menu a`  
b) `.menu a`  
c) `div.menu a`  
d) `.menu > a`

**Correct Answer:** b) `.menu a`

**Explanation:** The selector `.menu a` selects all `<a>` elements that are descendants of any element with the class `.menu`.

### 16. Advanced CSS Selectors
**Question:** Which selector will select only the first child `<li>` element inside any `<ul>`?

**Options:**
a) `ul li:first-of-type`  
b) `ul > li:first-child`  
c) `ul > li:first-of-type`  
d) `ul li:first-child`

**Correct Answer:** b) `ul > li:first-child`

**Explanation:** The selector `ul > li:first-child` selects the first child `<li>` element of any `<ul>`.

### 17. CSS Grid
**Question:** What does the following CSS grid code do?

```css
.container {
  display: grid;
  grid-template-areas:
    "header header"
    "sidebar main"
    "footer footer";
}
```
**Options:**
a) Creates a grid with 2 rows and 2 columns  
b) Creates a grid with 3 rows and 2 columns  
c) Creates a grid with 3 rows and 3 columns  
d) Creates a grid with 4 rows and 1 column

**Correct Answer:** b) Creates a grid with 3 rows and 2 columns

**Explanation:** The `grid-template-areas` property defines a grid layout with 3 rows and 2 columns based on the specified areas.

### 18. CSS Flexbox
**Question:** What does the following CSS code do?

```css
.container {
  display: flex;
  flex-direction: column-reverse;
}
```
**Options:**
a) Arranges flex items in a row in reverse order  
b) Arranges flex items in a column in reverse order  
c) Arranges flex items in a row in normal order  
d) Arranges flex items in a column in normal order

**Correct Answer:** b) Arranges flex items in a column in reverse order

**Explanation:** The `flex-direction: column-reverse` property arranges the flex items in a column in reverse order.

### 19. Advanced CSS Selectors
**Question:** How would you select every other row in a table?

**Options:**
a) `tr:nth-child(2n)`  
b) `tr:nth-child(odd)`  
c) `tr:nth-of-type(even)`  
d) `tr:nth-of-type(2n+1)`

**Correct Answer:** a) `tr:nth-child(2n)`

**Explanation:** The selector `tr:nth-child(2n)` selects every other row in a table, effectively selecting even rows.

### Advanced CSS Selectors
**Question 20** Which CSS selector will select only `<p>` elements that are immediately preceded by `<h2>` elements?

**Options:**
a) `h2 + p`  
b) `h2 ~ p`  
c) `h2 > p`  
d) `h2 p`

**Correct Answer:** a) `h2 + p`

**Explanation:** The adjacent sibling combinator (`+`) selects the element that is immediately preceded by the specified element. In this case, `h2 + p` selects all `<p>` elements that are immediately preceded by an `<h2>` element.