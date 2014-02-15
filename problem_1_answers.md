1. What does the colspan="3" attribute of the <th> node do?

The colspan attribute of <th> defines how many columns of the table the header should span. In this case, the header would be spanning three columns.


2. List all the styles (e.g. border width, text alignment, etc.) applied to the th element containing "Rank". For each, state whether they are set as an HTML attribute or a CSS style and describe them in a few words. Include only styles directly applied to the element, not styles inherited/cascading from parent elements or styles from the default user agent stylesheet. Exclude overwritten styles. For HTML attributes, state the CSS equivalent.

The following are the CSS styles attributes applied to the th that contains "Rank"
1) text-align: center; = This centers the text within the th cell.
2) font-weight: bold; = This makes the font bold.
3) border: 1px black solid; = This creates a 1pixel width border that is solid black in color. 
4) background-color: white; = This makes the background color of the cell white.

There are also HTML attributes applied to this th:
1) class: colhead_0; = This is attribute that points to the style and attributes of other elements of this class.
2) id = ascending; = This attribute helps determine whether clicking on the column head will sort the column ascendingly or descendingly.


3. What differences do you notice between the DOM inspector and the HTML source? Why would you use the DOM inspector? Why is the HTML source useful?

The DOM inspector shows you changes that were made dynamically (like in Javascript/d3), while the HTML source does not. The DOM inspector better shows you which attributes and styles are inherented by eache element in the view source tool. Using the DOM inspector, you can make changes to page dynamically which is powerful but can lead to some confusion because it does not involve any hard coding. 

You would use the DOM inspector if you want to dynamically change the page using javascript. The DOM helps you see how the JavaScript code is interacting with your web page.

The HTML source is useful when you need to keep track of the changes you are making. Changes made to the DOM are saved to a copy of the HTML, and if you leave unsaved changes in the HTML source, changes can easily get lost. It is often beneficial to stick to one method of making changes between saving the code.