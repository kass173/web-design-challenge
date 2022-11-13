# Web Design Challenge

Part 1: .............

Instructions
Create a website by using either the visualizations that you created for your Python-APIs Challenge or the weather data and images that are provided for this Challenge. To do so, use the considerations and website requirements that the following subsections describe. Also, ensure that your repository has regular commits and a descriptive README.md file.

Considerations
Be aware that you must use Bootstrap. This includes using the Bootstrap navbar component for the header on every page, the Bootstrap grid for responsiveness on the comparison page, and the Bootstrap table component for the data page.

Be aware that you must deploy your website to GitHub Pages, and that as a result, the website must work at a live, publicly accessible URL.

Make sure to use a CSS media query that uses Bootstrap and/or @media for the navigation bar.

Make sure that your website works at all window widths.

Feel free to take some liberties with the visual aspects, but keep the core functionality the same as the instructions describe. (For example, keep the comparison visualizations on the comparison page.)

## Latitude - Latitude Analysis Dashboard with Attitude

I created a visualization dashboard website for my previous project work, specifically, we'll be plotting [weather data](Resources/cities.csv), and the original GitHub respository found here [python-api-challenge](https://github.com/kass173/Python-api-Challenge)).

In building this dashboard, I created individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. I created also a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Contents

The website consist of 7 pages total, including:

### 1. Landing page
  * Containing an explanation of the project.
  * Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking an image will take to that visualization.
 
The view looks as follows:
  
Large screen:

![Landing page large screen](Images/landingResize.png)

Small screen:

![Landing page small screen](Images/landing-sm.png)
  
### 2. Four visualization pages 
  * With a descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
  
Large screen:

![visualize page large screen](Images/visualize-lg.png)

Small screen:

![visualize page small screen](Images/visualize-sm.png)

### 3. Comparisons page
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * I used a Bootstrap grid for the visualizations.
  * The grid has two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
 
Large screen:

![comparison page large screen](Images/comparison-lg.png)

Small screen:

![comparison page small screen](Images/comparison-sm.png)
                                   
### 4. Data page
  * In the data page I displayed a responsive table containing the data used in the visualizations.
    * The table is constructed by using a bootstrap table component.
    * The data come from exporting the `.csv` file as HTML.
Large screen:
![data page large screen](Images/data-lg.png)

Small screen:

![data page small screen](Images/data-sm.png)

Note:-
The website is at the top of every page, and have a navigation menu for plots, comparison, Data, and My page (Portfolio page)  
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* A dropdown menu created on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provided two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* A responsive navigation menu created by using media queries, and the background color will also change when it goes from large to small page.

Large screen:

![Navigation page large screen](Images/nav-lg.png)



Small screen:

![Navigation page small screen](Images/nav-sm.png)



