# Query by viz

<img src="https://repository-images.githubusercontent.com/257705174/bf43bf80-787f-11eb-90fb-902c4aa0c841"><br>
All ingredients needed exist in some shape or form. I just haven't seen them combined.
I see it as a general table filtering tool.

[Parallel Sets](https://ggforce.data-imaginist.com/reference/geom_parallel_sets.html) recalculated into [Parallel Coordinates](https://r-charts.com/ranking/parallel-coordinates-ggplot2/) is a good start. Let's try:

n1, n2, n3, etc., parallel_sets mapped on 0-1 parallel_coordinates<br>
N=sum(n1,n2,n3,..)<br>
stroke-width = 1/N<br>
y= (i-1/2) * (1/N)<br>

Within the set keep the same order as in the neighboring coordinates, or if you have coordinates on both sides, take a sort of average.

If built, it would help many more people from a proper home, therefore I suggested it to GGally: https://github.com/ggobi/ggally/issues/473

JMP software does [ParallelCoordinates and ParallelSets chart types combined in one chart](https://mobile.twitter.com/xangregg/status/1351639103293583360)<br>
<img src="https://pbs.twimg.com/media/EsH8AeqW8AMIgtm?format=webp&name=medium" width="20%"/>

Here you see the chart types coupled, but below each other, interacted with: [Parallel coordinates and parallel sets together](https://www.youtube.com/watch?v=SphrIOU76o0) seems like a great exploratory data analysis tool

To be reproducible (or replayable on a different data set) you need the GUI-actions captured and possible to replay:
[shinymeta, making GUI-actions reproducible](https://www.r-bloggers.com/2019/07/shinymeta%e2%80%8a-%e2%80%8aa-revolution-for-reproducibility-2/)

https://plotly.com/python/parallel-coordinates-plot/

Now if you could turn your shinyGUI-actions into the more generally used SQL, it would make it awesome power tool.
(tidyverse<>SQL things exist, e.g. https://dbplyr.tidyverse.org/articles/translation-verb.html ), would be close to perfect

# Possible application:

For material properties: [Ashby plots](https://en.m.wikipedia.org/wiki/Material_selection#Ashby_plots), also see https://www.ansys.com/products/materials/granta-edupack (Nog in Blackboard onder "Start" in lijst?)

# other exploratory data visualization:

[DataExplorer create_report() function in R](https://www.youtube.com/watch?v=A5e2ZajMFfY)

