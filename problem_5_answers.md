1. What's missing? Is this bar chart usable in its current form?

The bar chart is missing lables, a title, and corresponding values. While you may understand the gradation between elements in this current form, you do not have any context of why this bar chart was made. The title of the chart tells the user why they should care about the data visualization and the lables tell us what variables and relationships are being explored. Without these identifiers, the table is not usable in its current form.

2. What is the role of each of the three nested levels of g elements? (keep in mind you'll be adding a title to the chart)

The nested levels of the g elements are used from grouping. This beceause elements within the SVG contain similar attribute and thse are inherented in the <g> grouping. The first grouping is used to position the entire group of bars, the second is to apply characteristics that are uniform among group elements and so that the translation of the first grouping does not affect the grouping of each individual bar. The final nesting is to group the rate, state, and bar for each individual data item. 

3. Complete the implementation section below. Is there any consequence if you add the text elements before or after the rect elements? Why?

Yes, the bar covers the Rate text to some degree, which results in a font change when you add the text elements after the rect elements. This is because the black font is not covered in anyway by the bar. Thus, the text element appears on top of the rect when you put it before the rect element.