1. The domain() function is the data range upon which the scale is calculated. What does d3.selectAll("tbody tr")[0].length-1 mean?

This is the upper limit of the the data range upon which the scale is calculated, which is calculated by taking the "length" or number of elements in the array of rank values. It is the number of elements in the array of rank values minus one because arrays are indexed starting at 0. 

2. Add the snippet in your code. Describe, in words, what the following function calls return: color(0), color(10) and color(150)?

Color(0) function call returns orangered as it is the lower limit of this scale. Color(10) returns an orange color but less red than Color(0). Finally, Color(150) returns aqua because it is beyond the upper limit of the scale, which is 50.

3. If the array passed to domain() was the minimum and maximum rate values, how would that change the scale? In what situations would this be appropriate?

If the array passed to domain() was both the minimum and maximum rate values, the scale would not be as evenly distributed as it currently is. This is because the distribution appears normal and the difference betweeen adjacent ranks is not even throughout the set. If the steps between values were evenly distributed, it would make sense to pass the min and max values to domain().