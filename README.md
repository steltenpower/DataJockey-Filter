# Query by viz

Say you can filter your table of values on each axis as in this [Parallel Coordinates](https://plotly.com/python/parallel-coordinates-plot/) diagram.

Say in that thing you also allow categorical data, a.k.a. add [Parallel Sets](https://www.jasondavies.com/parallel-sets/) functionality.
This would set the line-width to height/n.
To show tiny categories, or many almost overlapping values, allow transforming the distribution. Maybe 
- resize categories to same size
- resize domains to have a similar number of inhabitants
- use transparency
- Also allow all 'empty' variants

Quick&dirty: Don't mix categorical and number values, have 1 parallel coordinates thing and 1 parallel sets thing, like https://www.youtube.com/watch?v=SphrIOU76o0
todo: add the youtube you used in the kwanti chat on Teams

Say based on the values of your graphical filtering you generate the WHERE clause of an SQL-query.


# related:
A handyman friend said it would be handy to filter on material properties [material selection](https://en.m.wikipedia.org/wiki/Material_selection#Ashby_plots)
