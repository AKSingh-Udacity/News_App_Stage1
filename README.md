# News_App_Stage1

My  sixth Project for Udacity Google  India Challenge  Scholarship.

The goal is to create a news feed app which gives a user regularly updated news from the internet


**ABOUT**
==========================================================================================================================================
This application is a News Feed App which fetches the news-data from Guardian API and displays it in a List format.

**PROJECT RUBRIC**
========================================================================================================================================
News App, Stage 1

#Layout

CRITERIA
MEETS SPECIFICATIONS
Main Screen

App contains a main screen which displays multiple news stories

List Item Contents

Each list item on the main screen displays relevant text and information about the story.

The title of the article and the name of the section that it belongs to are required field.

If available, author name and date published should be included. Please note not all responses will contain these pieces of data, but it is required to include them if they are present.

Images are not required.

Layout Best Practices

The code adheres to all of the following best practices:

Text sizes are defined in sp
Lengths are defined in dp
Padding and margin is used appropriately, such that the views are not crammed up against each other.
Funtionality

CRITERIA
MEETS SPECIFICATIONS
Main Screen Updates

Stories shown on the main screen update properly whenever new news data is fetched from the API.

Errors

The code runs without errors.

Story Intents

Clicking on a story uses an intent to open the story in the user’s browser.

API Query

App queries the content.guardianapis.com api to fetch news stories related to the topic chosen by the student, using either the ‘test’ api key or the student’s key.

JSON Parsing

The JSON response is parsed correctly, and relevant information is stored in the app.

No Data Message

When there is no data to display, the app shows a default TextView that informs the user how to populate the list.

#Response Validation

The app checks whether the device is connected to the internet and responds appropriately. The result of the request is validated to account for a bad server response or lack of server response.

Use of Loaders

Networking operations are done using a Loader rather than an AsyncTask.

External Libraries and Packages

The intent of this project is to give you practice writing raw Java code using the necessary classes provided by the Android framework; therefore, the use of external libraries for the core functionality will not be permitted to complete this project.

Code Readability

CRITERIA
MEETS SPECIFICATIONS
Readability

Code is easily readable such that a fellow programmer can understand the purpose of the app.

Naming Conventions

All variables, methods, and resource IDs are descriptively named such that another developer reading the code can easily understand their function.

Formatting

The code is properly formatted i.e. there are no unnecessary blank lines; there are no unused variables or methods; there is no commented out code.


**SCREENSHOTS**
======================================================================================================================================









**REVIEW RECEIVED FROM UDACITY REVIEWER**
=======================================================================================================================================
Meets Specifications
Hello Dear Student

**CONGRATULATIONS  :tada:  :trophy: :star:
You have done a great job on your News App Stage 1 app  :smile: and I can see that you have gone the extra mile by implementing advanced features like Settings Screen which is part of the next project. Your efforts and hard work haven't gone unnoticed. Very well done!  :clap:**

I have liked the clean and user-friendly UI with proper navigation.
Your code is clean, tidy, has adequate comments, and easy to read through  :clap:
The code works seamlessly and as expected.  :+1:

I have left some suggestions in each review section; hopefully, you will find them beneficial for your next projects.
In addition, I would recommend using Analyze > Inspect Code menu option in Android Studio as that will help unveil several corrections that are needed to
improve the code.
Will look forward to seeing more projects from you.

Once again, well done :smile:  :tada:  :clap: You're now one step closer to the finishing line 😊

Good luck with your next project :+1:

Keep learning. Stay Udacious. :v:

Regards

*Layout
App contains a main screen which displays multiple news stories

Awesome! the main screen displays multiple news stories :white_check_mark:

Each list item on the main screen displays relevant text and information about the story.

The title of the article and the name of the section that it belongs to are required field.

If available, author name and date published should be included. Please note not all responses will contain these pieces of data, but it is required to include them if they are present.

Images are not required.

Great! Each news item displays news title, news section, author name (where available) and published date along with the link.  :clap:

The code adheres to all of the following best practices:

Text sizes are defined in sp
Lengths are defined in dp
Padding and margin is used appropriately, such that the views are not crammed up against each other.
The code uses correct units for text sizes (sp) and lengths (dp). Also, padding and margin are used appropriately to make the layout look clean and
clutter-free. Very well done. :clap:

*Funtionality
Stories shown on the main screen update properly whenever new news data is fetched from the API.

Great! News stories are updated properly whenever new news data is fetched from the API. :white_check_mark:

The code runs without errors.

The app runs smoothly without any application errors. :clap:  :tada:

Clicking on a story uses an intent to open the story in the user’s browser.

Each story when clicked opens it in the browser. :white_check_mark:

App queries the content.guardianapis.com api to fetch news stories related to the topic chosen by the student, using either the ‘test’ api key or the student’s key.

Awesome! The app fetches news stories from Guardian API that are relevant to the topic chosen by the user.  :white_check_mark:

The JSON response is parsed correctly, and relevant information is stored in the app.

Great work on parsing the JSON correctly and fetching all relevant information needed. :clap:  :+1:

When there is no data to display, the app shows a default TextView that informs the user how to populate the list.

Excellent! A default TextView is shown when no news items are found to display.  :white_check_mark:

The app checks whether the device is connected to the internet and responds appropriately. The result of the request is validated to account for a bad server response or lack of server response.

Awesome! The app correctly checks for connectivity and displays an appropriate message when connectivity is lost. :+1:  :clap:

Networking operations are done using a Loader rather than an AsyncTask.

Awesome! The app uses AsyncTaskLoader for network operations. :+1:  :clap:
You can read more about it here why AsyncTaskLoader is preferred to AysncTask
https://google-developer-training.gitbooks.io/android-developer-fundamentals-course-concepts/content/en/Unit%203/71c_asynctask_and_asynctaskloader_md.html

The intent of this project is to give you practice writing raw Java code using the necessary classes provided by the Android framework; therefore, the use of external libraries for the core functionality will not be permitted to complete this project.

Code Readability
Code is easily readable such that a fellow programmer can understand the purpose of the app.

Code is easily readable and has adequate supportive comments  :+1:

All variables, methods, and resource IDs are descriptively named such that another developer reading the code can easily understand their function.

Great work on defining meaningful resource Ids, variables and method names :+1:

Here are a couple of tutorials that you might find useful in this context:
For XML resource IDs => https://jeroenmols.com/blog/2016/03/07/resourcenaming/
For Java variable and method names => https://google.github.io/styleguide/javaguide.html

The code is properly formatted i.e. there are no unnecessary blank lines; there are no unused variables or methods; there is no commented out code.

**RESOURSES USED**
====================================================================================================================================
Guardian website






