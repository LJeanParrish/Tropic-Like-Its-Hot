# Tropic Like It's Hot

![Images/tropic_like_hot.jpg](Images/tropic_like_hot.jpg)

## Background

Tropic Like It's Hot captured weather data from approximately 500 cities at different latitudes from the equator.  The objective was to create a dashboard reflecting my analysis on different weather phenomena and develop a website using HTML, CSS, and Bootstrap.

Individual pages were created for each plot and links were created to facilitate navigation between those plots. The plot pages contained the visualizations and their corresponding analysis.  I also created a landing page, a comparison page, and a page displaying the underlying data.
### Website Requirements


The website included a total of 7 pages with following schematics:

* A Landing Page containing:
  * An explanation of the project.
  * Links to each visualizations page. 
  * A sidebar containing preview images of each plot.  Clicking on an image navigated to that visualization.
* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization for the selected comparison.
  * A paragraph describing the plot and its significance.
* A Comparisons page that:
  * Contained all visualizations on the same page for easy comparison.
  * Used a Bootstrap grid for the visualizations.
    * The grid adjusted for screen size. 
* A Data page that:
  * Displayed a responsive table containing the data used for the visualizations.
    * The table utilized Bootstrap components. 
    * The data leveraged an exported `.csv` file that was then converted to HTML using Pandas.
* The website contained a navigation menu that:
  * Had the name of the site on the left allowing users to return to the landing page from any page.
  * Contained a dropdown menu on the right of the navbar that provided links to each visualization page.
  * Provided two text links for the "Comparisons" and "Data" pages.
  * Was responsive (used media queries). 

## Contact
Lauren Parrish
ljeanparrish@gmail.com