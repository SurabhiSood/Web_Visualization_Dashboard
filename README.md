### Goal -

To create a dashboard using HTML/CSS and Bootstrap to visualy represent the climate analysis we've done using pandas and matplotlib. The dashboard can be seen [here](https://surabhisood.github.io/index.html)

## Process

The first step was to assemble the analysis and the plots I have created using pandas and matplotlib. The analysis was done for at least 500 randomly selected cities around the world to prove that the weather gets hotter as one approaches the equator using the Open Weather Map API.

In building this dashboard, I created individual pages for each plot and a means by which we can navigate between them. These pages contain the visualizations and their corresponding explanations. I will also create a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

The website consist of 7 pages total, including:

* A 'landing page' containing:
  * An explanation of the project.
  * Links to each visualizations page.

* Four 'visualization pages', each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.

* A 'Comparisons page' that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.

* A 'Data page' that:
  * Displays a responsive table containing the data used in the visualizations.
    
The website, at the top of every page, has a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
