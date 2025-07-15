# Day 1: Introduction to CSS & Basics (0:00:00-1:11:56)
--
## Intro 
**Q:What is CSS?**
**A:**
 CSS(short of Cascading Style Sheets) is the language used to control the visual presentation of web documents written in HTML or XML. It controls colors, fonts, spacing, layout , and more. 
HTML builds the structure and CSS styles it visually.
--
## Start here
**Q: What are the three ways to apply CSS to an HTML document?**
**A:**
1. -Inline : 'style' attribute inside HTML tag.
2. -Internal: placing CSS rules inside a '<style>' tag in the '<head>'.
3. -External: writting CSS in a separate CSS file and linking it with <link> element.
--
## Selectors
**Q: What are the three main types of CSS selectors?**
**A:**
1.   -Element selector
2.   -Class selector 
3.   -ID selector
**Q: How can you select an element by its ID in CSS?**
**A:**
By using '#' symbol followed by the ID name.
**Q: What is the difference between a class selector and an ID selector in CSS?**
**A:**
1. -Class selectors: can be reused on multiple elements.
2.  -ID selectors : should be unique for a single element in the page.
**Q: How do you group multiple selectors in CSS?**
**A:**
 Use commas to separate selectors.
--
##Colors
**Q: Why is the property name "color" used in CSS instead of "colour"?**
**A:** 
Because CSS uses American English. So its "color" instead of "colour".
**Q: What are the different methods for setting a color value in CSS?**
**A:**
1. -Named colors
2. -Hexadecimal values
3. -rgb/rgba 
4. -hsl/hsla
**Q: How are CSS rules applied to elements? What are the three main factors?**
**A:**
1. -Specificity
2. -Order of appearance in the CSS file
3. -The use of !important
**Q: What is the purpose of !important in CSS, and why should it be used sparingly?**
**A:**
It forces the CSS rule to override any other rule.
**Q: How do you change the background color of a webpage?**
**A:**
 Just use background-color to the body tag.
--
##Units & Sizes
**Q: What are some common units used in CSS for sizing elements?**
**A:**
1. -Absolute units: px, pt, cm, in
2. -Relatives units: em, rem,%
3. -Viewport: vw, vh, vmin, vmax
--
##Box Model
**Q: What are the components of the CSS Box Model?**
**A:** 
1. -Content
2. -Padding
3. -Border
4. -Margin
**Q: What is the difference between `margin` and `padding` in the CSS Box Model?**
**A:**
1. -margin is the space outside the element (Between border and surrounding elements).
2. -padding is the space inside the element (between content and border).
**Q:Why do we use `CSS reset`?**
**A:**
To remove inconsistent default styling across different browser and provide a consistent base for styling. 
**Q: How does the `box-sizing` property affect the layout and size of an element?**
**A:**
1. -content-box: default value, padding and border are added outside the width.
2.  -border-box: padding and border are included inside the width.
**Q: What is the difference between `border` and  `outline`?**
**A:**
1. -border: affects layout and takes up space.
2.  -outline: does not affect layout and does not take up space.
**Q:What happens when a negative value is used in `outline-offset`?**
**A:**
The outline is drawn inside the element instead of outside.
**Q: How can you convert a square box into a circle using CSS?**
**A:** Apply border-radius of 50%.
**Q:What does the `border radius` do?**
**A:**
It rounds the corners of an element's border.
