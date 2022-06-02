# web-design-challenge

Created a website by using visualizations that were created in the Python-APIs challenge
* Created individual pages for each plot and navigate between them
  * Pages contain visualizations and descriptions with a main landing page 

Website consists of seven pages in total, including:
* Landing page containing
  * An explanation of the project
  * Links to each visualizations page containing preview images with links to the visualization page

* Four visualization pages, stored in the visualizations folder, each with the following elements:
  * A descriptive title and heading tag
  * Plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed)
  * A short sentence or two describing the plot and its significance

* A "Comparisons" page that does the following:
  * Contains all of the visualizations on the same page so they can easily be compared with each other

* A "Data" page that displays a responsive table containing the data used in the visualizations
  * Data is gotten from converting the .csv file to HTML using Pandas

* Every page has a navigation menu with the following elements:
  * Name of the site on the left of the navigation bar, allowing users to return to the landing page from any page
  * A dropdown menu named "Plots," to provide links to each individual visualization page
  * Text links: "Comparisons," which links to the comparisons page, and "Data," which links to the data page
