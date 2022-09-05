## Web-Design-Challenge
Repository that demonstrates the creation of HTML and CSS to create a dashboard featuring the Latitude vs. 'X' analysis of weather. Where X will be Max temperature, Humidity, Cloudiness, or Wind speed.

# MODULE 11 CHALLENGE - Web Development/Design

## Overview
The purpose of this project is to create a website by using visualizations of weather data and images. Using the considerations and website requirements as follows in the subsections below:

### Considerations
* Bootstrap must be used to include using the Bootstrap navbar component for the header on every page, the Bootstrap grid for responsiveness on the comparison page, and the Bootstrap table component for the data page.
* Website will be deployed on GitHub Pages, and that as a result, the website must work at a live, publicly accessible URL.
* Ensure the usage of a CSS media query that uses Bootstrap and/or @media for the navigation bar.
* Ensure that the website works at all window widths.


### Website Requirements
The websity will consist of seven pages. At the top of every page, the website will have a navigation bar. The website will be deployed to GitHub Pages. Below are the pages included in the website:

* Landing page - this page will contain the following elements:
  * An explanation of the project.
  * A link to each visualization page. For these, a sidebar will contain a preview image of each visualization. Clicking an image should take the user to that visualization.

* Four visualization pages, stored in the visualizations folder, each with the following elements:
  * A descriptive title and a heading tag.
  * The visualization for the selected comparison (latitude vs. max temperature, latitude vs. humidity, latitude vs. cloudiness, or latitude vs. wind speed). The images that these pages display will be stored in the assets/images folder.
  * A paragraph describing the visualization and its significance.

* A comparisons page that does the following:
    * Contains all the visualizations on the same page so that people can easily compare them.
    * Uses a Bootstrap grid for the visualizations. This grid will contain two visualizations across a medium or large screen and one visualization across an extra-small or small screen.

* A data page that displays a responsive table containing the data that the visualizations use, that is, a Bootstrap table component.