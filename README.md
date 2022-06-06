# Web-Design-Challenge 
#### Note this ReadMe is best viewed by clicking on README.md in the repository. 
Weather Analysis Web Page Demostrating Bootstrap
Demostration of dynamic page sizing and content alignment using the bootstrap grid system. A full function navigation bar with a dropdown element. The use of bootstrap tables. This repository represents a no frills framework application of these elements and would be a great jumping off point for you own project. There is very little custom .css (and it is well documented). Please see dependencies at the bottom of this document. 
***
### The landing page
Extra Large Screen - visualizations are displayed 4-up to the right and the navigation menu is displayed in full text.
![image](https://user-images.githubusercontent.com/98897041/172230853-bc98be19-ca88-404e-8645-62a3e4894832.png)

Large Screen - visualizations are displayed 4 in a row and below, the navigation menu is displayed in full text.
![image](https://user-images.githubusercontent.com/98897041/172231107-f0cc2680-2b1f-45e0-a639-76b097b99f69.png)

Medium/Small Screen(medium and small screen sizes behave the same)(shown in two images) - visualizations are displayed 4-up and below and the navigation menu is compressed. The image on the right (or below Depending on your screen size) shows the same screen with the navigation menu fully expanded.  
![image](https://user-images.githubusercontent.com/98897041/172235612-49d47efa-60c6-4fd3-8f92-e52183d86c7b.png)![image](https://user-images.githubusercontent.com/98897041/172237104-c8ea6101-2dc7-4c2e-83d1-6efdc3c7ef35.png)


Xsmall screen(shown in two images) - all screen objects are compressed to a single row navigation remains compressed and the navigation bar becomes blue. The image on the right (or below Depending on your screen size) is the same screen scrolled down. 

![image](https://user-images.githubusercontent.com/98897041/172231964-e90305e8-427c-4d5b-90eb-17c215254dad.png)![image](https://user-images.githubusercontent.com/98897041/172232296-bf20f5c6-0829-402b-8c63-7bc9018a7337.png)

### Plot Menu and Plot Thumbnails(also called visualizations)
Each of the visualizations on the landing page link to their respective visualization page, the plots navigation options also link to the visualization page. The visualization pages also include link thumbnails to each of the visualization pages. Each of these pages also include additional navigation to view the subset of data used in each of the visualizations and to regression analysis specific to that visualization. The one shown below is for temperature.

![image](https://user-images.githubusercontent.com/98897041/172238858-bfe261cc-f967-4a61-b18c-383e4f5305b8.png)

### Comparison Page
Conatains the thumbnail links to the visualization pages. Accessed through the navigation bar or button on visualization pages.

![image](https://user-images.githubusercontent.com/98897041/172240272-99694d70-e6a7-40e5-a65a-fa7a81794915.png)

### Data Page
The data page from the navagation menu displays a bootstrap table containing all of the data used for the analysis on the website. 
![image](https://user-images.githubusercontent.com/98897041/172241580-2888a19c-42d7-44a1-b56e-0fd9134701c0.png)

#### Data pages accessed from Visualization pages 
Display only the data used in this specific visualization. Cloudiness shown below.
![image](https://user-images.githubusercontent.com/98897041/172242450-fb04ad7e-ace1-447a-a839-9ab25282142a.png)
![image](https://user-images.githubusercontent.com/98897041/172242378-22fae0b1-376f-4b03-804b-ca6070c052b9.png)

### Regression Analysis Pages
Accessed from visualization pages, give a brief regression analalysis of the data by hemisphere and additional button navigation to the landing page(Home) the comparison page and the topic specific data page. Windspeed is shown below
![image](https://user-images.githubusercontent.com/98897041/172243845-8c2b296c-0bb6-4456-8f20-49f90221d716.png)

### All Pages
Contain a fully functioning navigation bar.  
Are fully responsive to size changes (illustrated in this document under the Landing Page section).   
Contain a footer not visible in most images giving credit and linking to the NOAA photo library - it's awesome, you should check it out. 
![image](https://user-images.githubusercontent.com/98897041/172244568-839d74b5-9f0f-4eae-a597-e51c3d20aa75.png)

### Credits and Dependencies 
bootstrap@5.2.0-beta1  
bootstrap-icons@1.8.3  
openweathermap.org   
NOAA Photo Library https://www.photolib.noaa.gov/  
***
To reproduce the data used in this project including visualizations you can use the following Jupyter Notebook    
https://github.com/LAFF1/Python-API-Challenge/tree/main/WeatherPy
The notebook has the following dependencies:
matplotlib | pandas | numpy | requests | time | scipy | termcolor | datetime  
You will also need an api key from [openweathermap.org](https://openweathermap.org/api)   
