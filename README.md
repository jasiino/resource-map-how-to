# How To Create Your Own Geo-Locator App

[![Image of 1](http://suffolklitlab.org/resource-map/HowTo%20Images/Video.png)](https://www.youtube.com/watch?v=qbPf9VRP6eU)
<p> A geo-locator app can be used to search for and filter through programs and services in your area. Click the video above watch the presentation explaining what a geo-locator app does and why it can be useful. Here are the steps to create your own geo-locator website application:
**<p> 1. Head to https://github.com/ and create your own account. </p>**
**<p> 2. Once you've created an account, go to https://github.com/SuffolkLITLab/resource-map-how-to. </p>**
**<p> 3. Click on the index.html file. </p>**
**<p> 4. Click the pen button to edit the code. </p>**
 
![Image of pen](http://suffolklitlab.org/resource-map/HowTo%20Images/pen.png)
**<p> 5. Copy the all the code from index.html. This is blank template where you will insert all the data needed. </p>**
**<p> 6. Click fork on the top right hand corner. </p>**
 
 ![Image of 1](http://suffolklitlab.org/resource-map/HowTo%20Images/1.png)
**<p> 7. Chose your profile to save under. Click the index.html file. Click the pen button to edit the code. </p>**
 
**<p> 8. Delete all existing code then paste the copied index.html code. </p>**
**<p> 9. Commit the changes on the bottom of the page. </p>**
 
![Image of Commit](http://suffolklitlab.org/resource-map/HowTo%20Images/Commit.png)
**<p> 10. Go to settings. Scroll down to GitHub Pages and turn on master branch. </p>**
 
 ![Image of Settings](http://suffolklitlab.org/resource-map/HowTo%20Images/Settings.png)
 ![Image of Settings2](http://suffolklitlab.org/resource-map/HowTo%20Images/Settings2.png)
 
**<p> 11. Change the name to what you would like as this is how it will show up in the URL. Go back to the repository. </p>**

![Image of Repo](http://suffolklitlab.org/resource-map/HowTo%20Images/Repo.png)
**<p> 12. Create an Airtable account [here](https://airtable.com). </p>**
 
![Image of Airtable sign in](http://suffolklitlab.org/resource-map/HowTo%20Images/Airtable%20sign%20in.png)
**<p> 13. Choose a base template that suits your needs. </p>**
 
![Image of Templates](http://suffolklitlab.org/resource-map/HowTo%20Images/Templates.png)
**<p> 14. Add tabs for all the different locations desired (i.e. Boston, Roxbury etc...) and add a "locations" tab. </p>**
 
![Image of Locations](http://suffolklitlab.org/resource-map/HowTo%20Images/Locations.png) 
**<p> 15. Under the "locations" tab, include the name, latitude & longitude coordinates, and zoom for each location. To find the latitude & longitude, you can use this [website](https://www.latlong.net). To add the zoom, add a comma then a number (i.e. ,13 ,14 ,15) to the end of coordinates. </p>**
 
![Image of Locations tab](http://suffolklitlab.org/resource-map/HowTo%20Images/Location%20tab.png) 
**<p> 16. Use the following headings for the different sections on the Airtable: Name, Category, Minimum age, Maximum age, Address, Description, Wesbite, Phone, Email, Valid As Of, Latitude, and Longitude. </p>**
 
![Image of Airtable](http://suffolklitlab.org/resource-map/HowTo%20Images/Airtable.png)
**<p> 17. Under the Category heading, create your own set of categories (i.e. community outreach, job opportunities/training, health services etc...). </p>**
**<p> 18. Conduct research on the programs you want to include. Begin inputting your own data into the Airtable. </p>**
**<p> 19. Turn to the index.html file. Click the pen button to edit. Update lines 7 & 34 to create your own title. </p>**
 
![Image of 7 34](http://suffolklitlab.org/resource-map/HowTo%20Images/7%2034.png)
**<p> 20. Update line 38 to include your own description. </p>**

![Image of 38](http://suffolklitlab.org/resource-map/HowTo%20Images/38.png)
**<p> 21. Update line 46 to describe age filter. </p>**

![Image of 46](http://suffolklitlab.org/resource-map/HowTo%20Images/46.png)
**<p> 22. Now turn to line 73 to update your own About page. </p>**

![Image of 73](http://suffolklitlab.org/resource-map/HowTo%20Images/73.png)
**<p> 23. Update line 142 to input your own Category names. Tag the categories as you want to refer to them throughout the code (i.e. "Alternative" "Risk"). </p>** 

![Image of 142](http://suffolklitlab.org/resource-map/HowTo%20Images/142.png)

**<p> 24. Put the tagged names into line 208. </p>**

![Image of 208](http://suffolklitlab.org/resource-map/HowTo%20Images/208.png)
**<p> 24. Go back to your Airtable. Find your API key. You can follow the steps below or go to this [website](https://medium.com/row-and-table/an-basic-intro-to-the-airtable-api-9ef978bb0729). </p>** 
 
![Image to Account](http://suffolklitlab.org/resource-map/HowTo%20Images/Account.png)

![Image to Account 2](http://suffolklitlab.org/resource-map/HowTo%20Images/Account%202.png)  

![Image to API Key](http://suffolklitlab.org/resource-map/HowTo%20Images/API%20Key.png)
**<p> 25. Copy and paste your API key in line 141 of the code. </p>**
 
![Image of 141](http://suffolklitlab.org/resource-map/HowTo%20Images/141.png)
**<p> 26. Find your API documentation. </p>**
 
![Image of API Documenation](http://suffolklitlab.org/resource-map/HowTo%20Images/API%20Documentation.png)

![Image of API Documentation 2](http://suffolklitlab.org/resource-map/HowTo%20Images/API%20Documentation%202.png)

![Image of API Documentation 3](http://suffolklitlab.org/resource-map/HowTo%20Images/API%20Doumentation%203.png)

**<p> 27. You can follow the steps above or go to this [website](https://medium.com/row-and-table/an-basic-intro-to-the-airtable-api-9ef978bb0729) to find your API Key and API Documentation. </p>**
**<p> 28. Copy and paste your API documentation in line 140 of the code. </p>**

![Image of 140](http://suffolklitlab.org/resource-map/HowTo%20Images/140.png)

**<p> 29. Find your Google Maps API. To find your Google Maps API go [here](https://developers.google.com/maps/documentation/javascript/get-api-key?refresh=1) and follow the steps below. You will likely have to sign into Google using a gmail account. </p>**

![Image Line Google API 1](http://suffolklitlab.org/resource-map/HowTo%20Images/Google%20API%201.png)
![Image Line Google API 2](http://suffolklitlab.org/resource-map/HowTo%20Images/Google%20API%202.png)
**<p> 30. Look at line 136 of the code. Insert your own Google API key. </p>**

![Image of 136](http://suffolklitlab.org/resource-map/HowTo%20Images/136.png)
**<p> 31. Go to settings again, scroll down to GitHub pages to find your own url link. </p>**

![Image of link](http://suffolklitlab.org/resource-map/HowTo%20Images/link.png)
