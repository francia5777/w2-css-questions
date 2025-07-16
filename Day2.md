# Day 2: Typography and Styling (1:37:08 - 3:00:21)

---

## Typography

**Q: What is typography in CSS?**  
**A:** Typography refers to all the visual styling of text including font, size, line height, spacing, and font family.

**Q: What does the font-size property do?**  
**A:** It sets the size of the text characters.

**Q: Why is line-height important?**  
**A:** It controls the vertical space between lines of text, improving readability.

**Q: How are letter-spacing and word-spacing different?**  
**A:** Letter-spacing adjusts space between letters, while word-spacing adjusts space between words.

**Q: What is the purpose of the font-family property?**  
**A:** It defines the font to use, and fallback fonts if the first isn’t available.

**Q: How do you add custom fonts to your CSS?**  
**A:**  
1. Use Google Fonts with `<link>` and `font-family`.  
2. Use `@font-face` to import a custom font manually.

---

## Styling Links

**Q: How does link styling differ from typography in CSS?**  
**A:** Link styling uses pseudo-classes like `:link`, `:visited`, `:hover`, and `:active`.

**Q: Why do links turn purple after being clicked?**  
**A:** Because browsers apply the `:visited` pseudo-class automatically.

**Q: What happens when the `:hover` pseudo class is applied to text?**  
**A:** The style changes temporarily when the mouse hovers over the element.

**Q: What is the `:active` pseudo class used for?**  
**A:** It applies styles while the element is being clicked.

**Q: Why is specificity order important in CSS?**  
**A:** It decides which style rule is applied when multiple rules target the same element.

**Q: How does the `:focus` pseudo class work?**  
**A:** It applies styles when an element gains focus (e.g. via keyboard).

---

## List Styles

**Q: What is the difference between ordered and unordered lists in CSS?**  
**A:** Ordered lists (`<ol>`) use numbers; unordered lists (`<ul>`) use bullets.

**Q: How many different types of ordered list styles are available in CSS?**  
**A:** Several like `decimal`, `upper-roman`, `lower-alpha`, etc.

**Q: How do `start` and `reversed` affect list numbering?**  
**A:**  
- `start` defines the starting number.  
- `reversed` makes the list count down.

**Q: How can you remove the default styling of a list?**  
**A:** Use `list-style: none;`.

**Q: How is `list-style-image` used?**  
**A:** It allows using a custom image as the bullet or marker.

**Q: What are different ways to override unordered list styles?**  
**A:**  
- `list-style-type`  
- `list-style-image`  
- Pseudo-element `::marker`

**Q: When to use `:nth-child` pseudo class?**  
**A:** To style a specific child element based on position.

**Q: What is `::marker` used for?**  
**A:** To style the bullet or number of a list item.

## Display

**Q: How is  a block element displayed compared to an inline element?**
**A:** A `block element` takes up the `full width` available and starts on a `new line`.
An `inline element` only takes up the width of its content and stays `in line with text`

**Q: When should the `none` value be displayed?**
**A:** The value display `none` is used when you want to hide an element completely from the page.

## Floats

**Q:How do you use `float` in CSS?**
**A:** By applying float:`left`; or float:`right`to make elements float next to each othe.

**Q:What are the possible values for the float property when positioning elements?**
**A:**
- `left`  
- `right`
- `inherit`  
- `none`  
**Q:What is the purpose of  the `clear` property?**
**A:** clear is used to stop elements from wrapping around floated elements.
