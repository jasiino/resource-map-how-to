# resource-maphowto
Resource-map how-to instructions
# How To Create Your Own Geo-Locator App
A geo-locator app can be used to search for and filter through programs and services in your area. Here is a [link](https://www.youtube.com/watch?v=qbPf9VRP6eU) to a presentation explaining what a geo-locator app does and why it can be useful. Here are the steps to create your own geo-locator website application:
**<p> 1. Head to https://github.com/ and create your own account.**
**<p> 2. Once you've created an account, go to https://github.com/SuffolkLITLab/resource-map-how-to.**
**<p> 3. Click on the index.html file.**
**<p> 4. Click the pen button to edit the code.**
 
![Image of pen](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/pen.png)
**<p> 5. Copy the all the code from index.html. This is blank template where you will insert all the data needed.**
**<p> 6. Click fork on the top right hand corner.**
 
 ![Image of 1](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/1.png)
**<p> 7. Chose your profile to save under. Click the index.html file. Click the pen button to edit the code.**
 
**<p> 8. Delete all existing code then paste the copied index.html code.**
**<p> 9. Commit the changes on the bottom of the page.**
 
![Image of Commit](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Commit.png)
**<p> 10. Go to settings. Scroll down to GitHub Pages and turn on master branch.**
 
 ![Image of Settings](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Settings.png)
 ![Image of Settings2](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Settings2.png)
 
**<p> 11. Change the name to what you would like as this is how it will show up in the URL. Go back to the repository.**

![Image of Repo](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Repo.png)
**<p> 12. Create an Airtable account [here](https://airtable.com).**
 
![Image of Airtable sign in](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Airtable%20sign%20in.png)
**<p> 13. Choose a base template that suits your needs.**
 
![Image of Templates](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Templates.png)
**<p> 14. Add tabs for all the different locations desired (i.e. Boston, Roxbury etc...) and add a "locations" tab.**
 
![Image of Locations](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Locations.png) 
**<p> 15. Under the "locations" tab, include the name, latitude & longitude coordinates, and zoom for each location. To find the latitude & longitude, you can use this [website](https://www.latlong.net). To add the zoom, add a comma then a number (i.e. ,13 ,14 ,15) to the end of coordinates.**
 
![Image of Locations tab](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Location%20tab.png) 
**<p> 16. Use the following headings for the different sections on the Airtable: Name, Category, Minimum age, Maximum age, Address, Description, Wesbite, Phone, Email, Valid As Of, Latitude, and Longitude.**
 
![Image of Airtable](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Airtable.png)
**<p> 17. Under the Category heading, create your own set of categories (i.e. community outreach, job opportunities/training, health services etc...).**
**<p> 18. Conduct research on the programs you want to include. Begin inputting your own data into the Airtable.**
**<p> 19. Turn to the index.html file. Click the pen button to edit. Update lines 7 & 34 to create your own title.**
**<p> 20. Update line 38 to include your own description.**

![Image Line 43 47](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Line%2043%2047.png)
**<p> 21. Update line 46 to describe age filter.**

![Image Line 55](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Line%2055.png)
**<p> 22. Now turn to line 73 to update your own About page.**

![Image Line 82](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Line%2082.png)
**<p> 23. Update line 142 to input your own Category names.** 

![Image Line 156](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Line%20156.png)

**<p> 24. Go back to your Airtable. Find your API key. You can follow the steps below or go to this [website](https://medium.com/row-and-table/an-basic-intro-to-the-airtable-api-9ef978bb0729).** 
 
![Image to Account](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Account.png)

![Image to Account 2](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Account%202.png)  

![Image to API Key](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/API%20Key.png)
**<p> 25. Copy and paste your API key in line 141 of the code.**
 
![Image Line 155](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Line%20155.png)
**<p> 26. Find your API documentation.**
 
![Image of API Documenation](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/API%20Documentation.png)

![Image of API Documentation 2](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/API%20Documentation%202.png)

![Image of API Documentation 3](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/API%20Doumentation%203.png)

**<p> 27. You can follow the steps above or go to this [website](https://medium.com/row-and-table/an-basic-intro-to-the-airtable-api-9ef978bb0729) to find your API Key and API Documentation.**
**<p> 28. Copy and paste your API documentation in line 140 of the code.**

![Image Line 154](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Line%20154.png)

**<p> 29. Find your Google Maps API. To find your Google Maps API go [here](https://developers.google.com/maps/documentation/javascript/get-api-key?refresh=1) and follow the steps below. You will likely have to sign into Google using a gmail account.**

![Image Line Google API 1](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Google%20API%201.png)
![Image Line Google API 2](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Google%20API%202.png)
**<p> 30. Look at line 136 of the code. Insert your own Google API key.**

![Image of Google](http://suffolklitlab.org/resource-map/HowTo%20Images/HowTo%20Images/Google.png)
