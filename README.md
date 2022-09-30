# Reader For Not Always Right

## Description

This is an android app that loads posts from the website notalwaysright.com, a site that I used to frequently visit. It will by default open each post made on the selected date(s) from the selected categories in a separate tab. Alternatively the posts can be opened inside the app one at a time. As the website only shows five articles at a time before needing to load a new page and reading the comments section for an article requires opening the page for that article, I found it convenient to load articles in bulk based on their category and the date that they were posted.

Made in Java using [Android Studio](https://developer.android.com/studio), [jsoup](https://jsoup.org/), and [ThreeTen Backport](https://www.threeten.org/threetenbp/). I selected jsoup for parsing the html from the Not Always Right website. ThreeTen Backport was utilized so that I could use the JSR-310 API (Java 8 date and time library) on devices that did not support it (such as the Samsung Galaxy S5).

## Installation

You can download NotAlwaysRightReaderForAndroid.apk and open it on your android device to install it. You will need to enable sideloading to do this if you have not done so prior. Alternatively, you can download or clone the repository and compile it yourself in android studio to generate your own apk file.

## Instructions

![image](https://user-images.githubusercontent.com/111155048/191289905-66ef47b2-b3b9-46d1-a867-fea326ab9be1.png)

The first time you use the app you should use the gear in the upper right hand corner to select the settings you want to use. You can choose from 3 methods of selecting dates (one date, consecutive range of dates, or list of dates), whether you want posts opened in the app or your browser, and if the app should only open articles that you have not opened before. An article is marked as read when the app sends it to your browswer to open or is opened in the app. This menu also includes the option to reset the list of read articles.

![image](https://user-images.githubusercontent.com/111155048/191288181-5e0cadbe-f94c-4710-8b3a-9c4bffaa65ba.png)

On the main page of the app simply choose the date(s) you wish to view posts on and then choose the category you want the posts to be from. The bottom row of buttons scrolls horizontally to reveal more categories. After a short wait (the length of the wait is greater when looking for older posts) the posts will open in your browser, or a button will appear to view them in the app (depending on your chosen settings). 

## About the Author

### Rishi Pathak

This is the second android app that I completed. 

LinkedIn: [here](https://www.linkedin.com/in/rishispathak)
