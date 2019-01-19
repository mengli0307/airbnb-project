# airbnb-project
This project includes two parts. The first one is the data cleaning and reviews translation part named as 'translate.ipynb', second one is the interface part named as 'recomandation platform interface.ipynb'.

For the data cleaning part, it includes some basic data cleaning steps. Specifically for airbnb data, it includes many reviews in different language, so we need to detect languages and translate them to English before other analytics. So this file also contains detecting part and translating part using Microsoft Translate API. 

For the interface part, I utilized tkinter package to create the main window. The problem that we want to slove in this part is to find the best listing in a certain area that fits their expectations in terms of price. So firstly we get the latitude and longitude based on the name of landamrk based on bing Map API. Secondly calculate the distance between each listing and landmark and retrieve appropraite ones based on radius offered by customers. And then check the price of listings. Lastly rank the results by sentiment scores. 
