# Web Visualization Dashboard 


For this project, I created a website by using the [weather data](Resources/cities.csv) provided. This is the final website: https://afiaella.github.io/Web-Visualization-Dashboard/

While building this dashboard, I created individual pages for each plot and a way to navigate between them. These pages containe the visualizations and description. I also buildt a landing page to provide a comparison of all the plots, along with another page to present the data used to build them.

### Website Contents

The website must consisted of seven pages in total, including:

* A landing containing the following elements:

  * An explanation of the project

  * Links to each visualizations page. 
  
  <img width="887" alt="image" src="https://user-images.githubusercontent.com/85926823/195675850-26d61c72-4a35-4d8b-a741-f0b947e158e2.png">


* Four visualizations pages, stored in the `visualizations` folder, each with the following elements:

  * A descriptive title and heading tag.

  * The plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed). 
  
  * A paragraph describing the plot and its significance.
  <img width="794" alt="image" src="https://user-images.githubusercontent.com/85926823/195676021-a428f1bc-6ba3-4703-a9f8-444118946ec9.png">


* A Comparisons page that does the following:

  * Contains all of the visualizations on the same page so they can easily be compared with each other.


* A data page that displays a responsive table containing the data used in the visualizations.

  * The data comes from exporting the  by converting the `.csv` file to HTML. Using Pandas. Pandas has a method, appropriately called `to_html`, that allows you to generate an HTML table from a Pandas DataFrame. 
  
  <img width="854" alt="image" src="https://user-images.githubusercontent.com/85926823/195676179-7778fa3f-eb05-4ec5-81b7-d7aa29b761b2.png">


At the top of every page, the website has a navigation menu with the following elements:

* It has the name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.

* It contains a dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.

* It provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

<img width="518" alt="image" src="https://user-images.githubusercontent.com/85926823/195676278-8abe94e6-d041-4120-9b51-df0093722efc.png">



Finally, the website was deployed to GitHub Pages.



