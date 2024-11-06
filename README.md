# CSS Box Model Example
# Description
This project demonstrates the use of the CSS Box Model by creating three div elements with different background colors, borders, padding, and margins. The goal is to visualize how these CSS properties work together to shape the layout of a webpage.
# Features
Three div boxes with varying background colors and sizes.
Each box demonstrates different CSS Box Model properties: padding, border, and margin.
A paragraph inside the first div element that showcases how padding affects content placement.
# Project Requirements
Create three div elements on the page.
Set their height and width to 200px by 200px.
Set unique background colors for each div.
Add a <p> element inside the first div with sample text (Lorem Ipsum).
Apply padding and borders to each div to experiment with the Box Model.
Remove the default margins of the <p> element inside the first div.
Set the second div to have different border widths for the top/bottom and left/right.
Adjust the margins for the boxes to make the corners of each div touch.
# CSS Box Model Explained
The CSS Box Model describes the rectangular boxes generated for elements in the document tree, consisting of:

Content: The actual content of the box (e.g., text, images).
Padding: Clears an area around the content, inside the border. The padding is part of the element's total size.
Border: Surrounds the padding (if any) and content. Borders have width, color, and style.
Margin: Clears space outside the border, separating elements from each other.
# Instructions
Clone or download the repository.
Open the index.html file in a web browser to see the layout.
Open the developer tools (in Chrome or Firefox) to inspect the Box Model properties using the CSS inspector.
# File Structure
bash
Copy code
/project-folder
  ├── index.html          # The main HTML file containing the structure
  └── style.css           # The CSS file with the styles for the project
# CSS Styles
The following CSS styles have been applied to the div elements:

#first:

Background color: cadetblue
Border: 10px solid black
Padding: 20px
Contains a <p> element with text
#second:

Background color: gold
Border: Solid black with 20px for top and bottom, 10px for left and right
Margin-left: 260px (positioning it to the right)
#third:

Background color: indianred
Border: 10px solid black
Margin-left: 40px (positioning it slightly to the right)
# Preview
You can view the rendered layout in any modern browser. Each div will have its unique appearance based on the applied styles and the Box Model properties.
