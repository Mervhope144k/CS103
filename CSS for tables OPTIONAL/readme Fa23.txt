Fa23     Felke book (tables) Optional Stuff
updated 1-18-2015, 5-16, 11-18, 11-19, 3-21, 4-22


CSS for tables

Code to study and play with involving tables and related CSS. Many of the CSS styles we have already learned. Examples: 
	border with "wall street crisis" (border: width style color)
	padding
	width
	background-color (or background)
	


Observe table_css_11142018_1. Then observe table_css_11142018_2 which develops the table_css_11142018_1 further. Also take note of the following:

1) Take a look at the border-collapse style:
	border-collapse: separate
   	border-collapse: collapse

The value "separate" is the default value. It renders both the outer border around the whole table AND the borders around each cell. The second value "collapse" collapses the outer table border and the cell borders into one border, with the outer table border style overruling. It looks cleaner. 

2) In the HTML code, each book title was marked as class="book-title" . The following 
	.book-title {display: block} 

was applied to each book's title which makes it block level (or grouping level). Thus each book title starts on its own line in the cell, above the publisher name. Likewise, each publisher name in each cell was marked as classname="publisher" and styled as display: block.

3) By my experimenting, 
If you apply border styles to the table element it controls the outer border.
If you apply border stlyes to the th and td elements, it controls the inner borders or gridlines around each cell.



citation: HTML and CSS by Shay Howe.