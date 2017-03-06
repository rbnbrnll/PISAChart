# PISAChart
Analysis of 2012 PISA data with regards to math performance and influential dynamic

# Summary
This report explores a dataset containing results from the Program for International Student Assessment(PISA).  My analysis compares average test scores for students in Canada and the United States and how they relate to three questions from the exam.  Each question pertains to a different group of people, namely friends, parents, and teachers.  The graphic shows the relationship between these groups and student performance.

# Design
After drawing several sketches of the data I decided using a bar chart in the final graphic was most appropriate.  Four different variables are represented in the graphic: Average score, Country, Question, and student reponse.  This fact made creating a visualization that showed all the relationships a challenge.  
I realized after my first review that the graphic needed an introduction and better clarification on what the horizontal axis was trying to represent.  After the 2nd reviewer critiqued it I decided to try a side by side bar chart which can be seen in index5.html.  The third reviewer thought stacked would be better as did the first reviewer so a stacked bar chart was the final choice.  Placing the conclusions directly below each question made sense rather than putting them off to the side or stacked.
I decided to remove the default x-axis as the ticks were not really needed nor was the line.  Modyifying the default tooltip to have more meaningful data rather than column names also seemed reasonable.  My original thought was to represent Canada in red as that is the predominate color in their flag but opted to use a softer color as recommended in the Udacity Data Visualiaztion course.  Reports produced on the PISA website did not include NA data so I did not put them in my visusalization.


# Feedback
## BG's feedback on index2.html
### What do you notice in the visualization?
The title does not match what the data is trying to show.
### What relationships do you notice?
None, too confusing.
### Is there something you don't understand in the graphic?
A lot, not sure what the x-axis is about, needs clarification.
## ML's feedback on index2.html
### What do you notice in the visualization?
Did not notice the legend.  Canada on top of US is confusing, should be side by side not stacked
### Is there something you don’t understand in the graphic?
Not very clear which country got which score.  Need better explanation at the beginning.
## BB's feedback on index5.html
### What do you notice in the visualization?
Labels on bars are confusing, order of countries in legend don’t match the order of the bars.
### What relationships do you notice?
Kind of confusing with so many bars
### What do you think is the main takeaway from this visualization?
In Canada students respond differently to external factors than do US students.
## BG's feedback on index5.html
### What do you notice in the visualization?
Prefer stacked bars rather than side by side.  I like the new descriptions below the graph.
### What relationships do you notice?
Teacher’s amount of help doesn’t seem to matter in the US.

# Resources
view-source:http://bl.ocks.org/yavigol/raw/fbb6a04160e1c3ee4731/

http://annapawlicka.com/pretty-charts-with-dimple-js/

http://dimplejs.org/examples_viewer.html?id=area_steps_vertical_grouped_100pct

http://dimplejs.org/adhoc_viewer.html?id=adhoc_bar_custom_tooltips

http://stackoverflow.com/questions/11069278/javascript-if-else-shorthand

https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.chart#setMargins

http://stackoverflow.com/questions/26009100/dimple-js-d3-js-auto-size-chart-when-window-size-changes

https://github.com/PMSI-
AlignAlytics/dimple/wiki/dimple.axis#overrideMin

http://cpettitt.github.io/project/dagre-d3/latest/demo/style-attrs.html

http://bl.ocks.org/d3noob/ccdcb7673cdb3a796e13

http://stackoverflow.com/questions/11252753/rotate-x-axis-text-in-d3

http://dimplejs.org/examples_viewer.html?id=areas_curvy

http://www.oecd.org/pisa/pisaproducts/datavisualizationcontest.htm

https://www.oecd.org/pisa/pisaproducts/pisadataanalysismanualspssandsassecondedition.htm

https://discussions.udacity.com/t/question-to-dataset-pisa/21365

https://nces.ed.gov/surveys/pisa/pdf/PISA2009CB_quickguide.pdf

https://www.oecd.org/pisa/pisaproducts/PISA%202012%20Technical%20Report_Chapter%2019.pdf

OECD (2009), PISA Data Analysis Manual: SAS, Second Edition, OECD Publishing, Paris.
DOI: http://dx.doi.org/10.1787/9789264056251-en

https://www.oecd.org/pisa/pisaproducts/PISA%202012%20Technical%20Report_ANNEX%20B%20%E2%80%93%20CONTRAST%20CODING%20USED%20IN%20CONDITIONING.pdf

https://discussions.udacity.com/t/pisa-2012-mean-scores-confusion/33479/3

http://www.keepeek.com/Digital-Asset-Management/oecd/education/pisa-data-analysis-manual-sas-second-edition/analyses-with-plausible-values_9789264056251-9-en#.WJuCZG8rKHs#page4
