# Web-Visualization-Dashboard-Project

This Web Visualization Dashboard Project was written/executed by Radha Mahalingam on 4-29-19

## Background

Data is more powerful when we share it with others! Here I have implemented what I have learned about HTML and CSS to create a dashboard showing off the analysis that was performed.

## Latitude - Latitude Analysis Dashboard with Attitude

For this homework/project, I have created a visualization dashboard website using visualizations that I have created in a past assignment. Specifically, I will be plotting [weather data](Resources/cities.csv).

In building this dashboard, I have created individual pages for each plot and a means by which we can navigate between them. These pages  contain the visualizations and their corresponding explanations. I have also created a landing page, a page where everyone can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

In order to provide better visualization of the data analysis done on the weather data. The website consist of 7 pages total, which are as follows :

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid has two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The data has come from exporting the `.csv` file as HTML, or converting it to HTML. 

The website, at the top of every page, have a navigation menu that:

   * Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
   * Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
   * Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
   * This site is responsive, which uses media queries. The nav  have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, I have deployed the website to GitHub pages.

   I am submitting to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

