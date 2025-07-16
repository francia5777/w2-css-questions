# Day 3: Layout & Positioning (3:12:46 - 4:21:39)

---

## Columns

**Q: How can you create a multi-column layout using CSS?**  
**A:** By using `column-count` to specify the number of columns or `column-width` to define the width. You can also use the shorthand `columns`.

**Q: What is the shorthand for writing `column-count` in CSS?**  
**A:** `columns: 3 200px;` sets 3 columns each with a width of 200px.

**Q: What does the `column-rule` property do?**  
**A:** It adds a dividing line between columns.

---

## Position

**Q: What is the difference between `relative`, `absolute`, `static`, `sticky` and `fixed` positioning and define each of them?**  
**A:**
- `static`: Default position.
- `relative`: Moves relative to its normal position.
- `absolute`: Positioned relative to the nearest positioned ancestor.
- `fixed`: Fixed in the viewport even when scrolling.
- `sticky`: Switches from relative to fixed when it hits a defined scroll position.

**Q: How do you make a div take up the full width of its parent?**  
**A:** By using `width: 100%;`

**Q: How can you make an element sticky on the page while scrolling?**  
**A:** By using `position: sticky;` and define an offset like `top: 0;`

**Q: What does `z-index` control?**  
**A:** The stacking order of elements along the z-axis.

---

## Flexbox

**Q: How do you center a div using Flexbox?**  
**A:**
- `display: flex`;
- `justify-content: center`;
- `align-items: center`;
**Q: How does flex-direction work?**  
**A:** It sets the direction of items: row, row-reverse, column, or column-reverse.

**Q: How do you add space between your elements using Flexbox?**  
**A:** By using `justify-content: space-between` or  `space-around` or `space-evenly`.

**Q: How do you control an overflow element?**  
**A:** By using `overflow: auto` or `scroll` or `hidden`.

**Q: What is the difference between flex-grow and flex-shrink?**  
**A:**

- `flex-grow`: Allows an item to grow if extra space is available.

- `flex-shrink`: Allows an item to shrink if space is tight.

**Q: What is the purpose of flex-shrink?**  
**A:** It defines how an item reduces its size when the container is too small.
---
## Grid Layout

**Q: What are the different ways to apply a grid to a webpage?**  
**A:** By using `display: grid` or `display: inline-grid`.

**Q: What are grid-template-columns and grid-template-rows?**  
**A:** They define the number and size of the columns and rows in the grid.

**Q: How does CSS Grid differ from Flexbox?**  
**A:**

- Grid is for 2D layouts.

- Flexbox is for 1D layouts.

**Q: What is an absolute value and fraction unit in CSS grid?**  
**A:**
- absolute value: fixed units like px, %.
- fraction unit: divides remaining space proportionally.

**Q: What is the purpose of grid-template-areas?**  
**A:** It allows naming sections of a layout for easier placement.
