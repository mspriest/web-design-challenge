# web-design-challenge

### Objective:

Using CSS/HTML & Bootstrap, create a visualizations using the city weather dataset (weather_data.csv) & images (assets folders) from the python-api-challenge.

Bootstrap elements include a responsive navbar, columns and table as well as customized theme (boostrap.min) via Bootswatch. Additional styling was also applying using CSS (styles.css)

This website has also been deployed to GitHub pages: https://mspriest.github.io/web-design-challenge/

### Website Content:

The website consists 7 pages total, including:

* A **landing page** (index.html) containing:
  * An explanation of the project.
  * Links to each visualizations page containing preview images of each plot; images are clickable and will take the user to that visualization.
* Four **visualization** pages (visualizations.html) each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A **comparisons** page (comparisons.html) that:
  * Contains all of the visualizations on the same page for easy comparison.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A **data** page that:
  * Displays a responsive table containing the data used in the visualizations.
    * A table containing a bootstrap element (i.e., responsive table) 
    * Data exported from the `.csv` file (weather_data.csv) as HTML/converted to html (htmldata.html) using a pandas dataframe (weather_data_html.ipynb)