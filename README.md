# rlb-4k-3-lines-Bacon-html-text-scroller
BACon project to scroll text across 3 lines from the bottom right to the upper left corner

In this repo you will find a BrightAuthor:Connected (BACon) exported project that will allow you to scroll text from a User variable or from a BBC RSS feed.

Please see the below video for a peek preview of what to expect:

[video preview here](https://brightsigninfo-my.sharepoint.com/:v:/g/personal/rlucinab_brightsign_biz/EW_YguAarlJPgN9qmoS2CxQBIYzlfYNyHfUnU3v6TUKVwg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=S8a73R)

## Getting Started

1. Download and unzip the zip file

   <img width="881" alt="image" src="https://github.com/user-attachments/assets/8f35a124-ef55-483f-bc71-b4b99fdf871a">

2. With BACon 1.44.0 (or newer) open the presentation
3. Publish the presentation to a XT5 or XC5 player (only tested on a XT5 player)

At this point you should see the player scrolling either the content of the user variable "textvalue" or the technology BBC RSS feed [BBC RSS Feed](https://feeds.bbci.co.uk/news/technology/rss.xml)

## How do I switch from scrolling the User variable or the RSS feed?

Go to the player User variable page "http://xxx.xxx.xxx.xxx:8008" and set the value of the "feedORtext" User variable to either "feed" or "text" then click on the "Set Values" button.

<img width="925" alt="image" src="https://github.com/user-attachments/assets/0c71f437-7dd9-4985-b81d-c0b2486e85d5">

## How do I change the content of the "textvalue" user variable to be scrolled on screen?

Go to the player User variable page "http://xxx.xxx.xxx.xxx:8008" and set the value of the "textvalue" User variable to the new text that you want to scroll across the screen then click on the "Set Values" button.

<img width="937" alt="image" src="https://github.com/user-attachments/assets/d7ca7a5b-c536-4507-a7aa-03fa04d4eef0">

## How do I change the RSS feed to be scrolled on the screen?

In the BACon presentation, go to "Presentation Settings" > "Support Content" > "Data Feeds" > "Data Feed" > URL > then replace the current URL for the data feed with the URL of your new RSS feed

<img width="367" alt="image" src="https://github.com/user-attachments/assets/79748099-8de4-4b11-93bf-f948f013354f">

## How do I adjust the number of articles to be scrolled on the screen?

Go to the player User variable page "http://xxx.xxx.xxx.xxx:8008" and set the value of the "articleNumber" User variable to the prefered number of articles to be scrolled (default value is 10)

<img width="928" alt="image" src="https://github.com/user-attachments/assets/eeb46d1a-7318-462e-a682-899deadcde49">

## How do I adjust the speed of the scroll?

In the index.html file provided in this repo there is a "speed" variable that can be adjusted in the Javascript code

<img width="924" alt="image" src="https://github.com/user-attachments/assets/d86fdaa9-bf07-4b6a-bfa4-2fff7cb0566d">

## How do I adjust the look and feel of the text scroller?

The look and feel (background color, font size, font color, etc) of the scroller and text can all be manually adjusted in the index.html file. Make sure to republish the presentation once you've made the necessary changes to the index.html page.

