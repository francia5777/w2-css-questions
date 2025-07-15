# Day 1: Introduction to CSS & Basics (0:00:00–1:11:56)

---

### Intro

**Q: What is CSS?**  
**A:**  
CSS (short for Cascading Style Sheets) is the language used to control the visual presentation of web documents written in HTML or XML. It controls colors, fonts, spacing, layout, and more. HTML builds the structure and CSS styles it visually.

---

### Start Here

**Q: What are the three ways to apply CSS to an HTML document?**  
**A:**  
- Inline: using the `style` attribute directly inside an HTML tag  
- Internal: placing CSS rules inside a `<style>` tag within the `<head>`  
- External: writing CSS in a separate file and linking it using `<link>`

---

### Selectors

**Q: What are the three main types of CSS selectors?**  
**A:**  
- Element selector  
- Class selector  
- ID selector

**Q: How can you select an element by its ID in CSS?**  
**A:**  
By using `#` followed by the ID name.

**Q: What is the difference between a class selector and an ID selector in CSS?**  
**A:**  
- Class selectors can be reused on multiple elements.  
- ID selectors should be unique for a single element on the page.

**Q: How do you group multiple selectors in CSS?**  
**A:**  
Use commas to separate the selectors.

---

### Colors

**Q: Why is the property name "color" used in CSS instead of "colour"?**  
**A:**  
Because CSS uses American English. So it uses "color" instead of "colour".

**Q: What are the different methods for setting a color value in CSS?**  
**A:**  
- Named colors  
- Hexadecimal values  
- rgb / rgba  
- hsl / hsla

**Q: How are CSS rules applied to elements? What are the three main factors?**  
**A:**  
- Specificity  
- Order of appearance  
- Use of `!important`

**Q: What is the purpose of `!important` in CSS, and why should it be used sparingly?**  
**A:**  
It forces a rule to override all others, but it should be used sparingly because it makes CSS harder to maintain.

**Q: How do you change the background color of a webpage?**  
**A:**  
Apply `background-color` to the `body` tag.

---

### Units & Sizes

**Q: What are some common units used in CSS for sizing elements?**  
**A:**  
- Absolute units: `px`, `pt`, `cm`, `in`  
- Relative units: `em`, `rem`, `%`  
- Viewport units: `vw`, `vh`, `vmin`, `vmax`

---

### Box Model

**Q: What are the components of the CSS Box Model?**  
**A:**  
- Content  
- Padding  
- Border  
- Margin

**Q: What is the difference between `margin` and `padding` in the CSS Box Model?**  
**A:**  
- `margin`: space outside the element  
- `padding`: space inside the element (between content and border)

**Q: Why do we use `CSS reset`?**  
**A:**  
To remove default styling differences between browsers and ensure consistent rendering.

**Q: How does the `box-sizing` property affect the layout and size of an element?**  
**A:**  
- `content-box`: padding and border are added to the width  
- `border-box`: padding and border are included inside the width

**Q: What is the difference between `border` and `outline`?**  
**A:**  
- `border`: affects layout and takes up space  
- `outline`: doesn’t affect layout or take up space

**Q: What happens when a negative value is used in `outline-offset`?**  
**A:**  
The outline is drawn inward (inside the element) instead of outside.

**Q: How can you convert a square box into a circle using CSS?**  
**A:**  
Apply `border-radius: 50%`

**Q: What does the `border-radius` do?**  
**A:**  
It rounds the corners of an element’s border.