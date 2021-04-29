# HousePricePrediction

The flask Python website that predict price of a house/property using a machine learning model.

<ul>
<li>First we build a model using sklearn and linear regression using banglore home prices dataset from kaggle.com.</li>
<li>Second we write a python flask server that uses the saved model to serve http requests.</li>
<li>Third component is the website built in html, css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price.</li>
</ul>

<h2>Screen Shots<h2>
<img  src="ScreenShots/1.PNG" alt = "ScreenShot 1" width = "500" height = "600"> 
<img  src="ScreenShots/2.PNG" alt = "ScreenShot 2" width = "500" height = "600"> 
<img  src="ScreenShots/3.PNG" alt = "ScreenShot 3" width = "500" height = "600">
<img  src="ScreenShots/4.PNG" alt = "ScreenShot 4" width = "500" height = "600"> 
<img  src="ScreenShots/5.PNG" alt = "ScreenShot 5" width = "500" height = "600"> 

To run this website on your local machine, You need to install requirements.txt by using

<i>pip install -r requirements.txt<i> command.

After installing above dependencies you can run the server using

$ python server.py

and open app.html on any browser.

