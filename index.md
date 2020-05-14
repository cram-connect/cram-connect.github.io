<title>Cram Connect</title>

## Table of Contents
* [Overview](#overview)
* [Goals](#goals)
* [Galaxy Deployment](#galaxy-deployment)
* [GitHub Organization](#github-organization)
* [User Guide](#user-guide)
* [Milestones](#milestones)
* [Developer Guide](#developer-guide)
* [Community Feedback](#community-feedback)
* [Development Team](#meet-the-development-team)

## Overview
Cram connect a website that will allow students to post and rate study spots throughout the UH Manoa campus and the surrounding areas so that other students become aware of possible study spots. The entry for each location will list hours, capabilities, capacity of the location, and accessibility to different types of students. In the future, Cram Connect would greatly benefit from a “real-time” feature, where students can login and provide time-stamped notifications about the current state of the study space. This would inform other students about whether the space is noisy, or crowded, or even quiet and empty.

## Goals
To provide a intuitive user interface that can provide an efficient system to allow students to discover and rate study spots in and around the UH Manoa campus.

The system should eventually provide a sign-in system that allows the user to edit their preferences, filter out study spaces to find an appealing location, and receive real time notifications about the current state of study spaces. After the initial development of our website, we hope to add additional features to Cram Connect, including maps information about study spaces and a news feed of the latest updates on users' favorite locations.

## Galaxy Deployment
"Cram Connect is deployed using Galaxy. Due to the expiration of our free trial, our site cannot be accessed through Galaxy at this time."

...is what we would normally say. However, we were able to get a friend, outside of our group, to register for a free trial, and we were able to deploy our app via Galaxy. Check it out [here](http://cram-connect.meteorapp.com/#/), or by pasting the following in the web browser:
```
http://cram-connect.meteorapp.com/#/
```

## GitHub Organization
The GitHub organization for Cram Connect can be accessed [here](https://github.com/cram-connect), or by pasting the following in the web browser:
```
https://github.com/cram-connect
```

## User Guide
Our user guide, provides a breakdown of the Cram Connect website.

### Landing page
The landing page is the top-level URL for the Cram Connect website.
![](images/M1/landing.jpg)

### Sign in
The user can login in to manage their account and interact with the Cram Connect community.
![](images/M2/signin.JPG)

### Register
The user can create a new account by filling in the appropriate fields.
![](images/M2/register.JPG)

### Search
The search page will allow each user to search for study spots to find the best study environment.
![](images/M3/search.png)

NOTE: The filter on the left side does not currently work, but the search and selection of the cards to go to the location are functional.

### Study Location
The user can take a look at each study location and find out more information about them.
![](images/M3/location.png)

### Favorites
User can view the status of their selected favorite locations.
![](images/M3/favorites.png)

### User Profile
The user can edit their profile with their information and preferences.
![](images/M2/editProfile.jpg)

### Discover
The user can find a random study location that is not in their favorites.
![](images/M3/discover.png)

NOTE: The user can favorite the site when accessed through the discover page, but the button will not update in color.

## Milestones
Each milestone project page can be accessed with the links below.
* [M1 Project: Milestone 1](https://github.com/cram-connect/cram-connect/projects/2)
* [M2 Project: Milestone 2](https://github.com/cram-connect/cram-connect/projects/1)
* [M3 Project: Milestone 3](https://github.com/cram-connect/cram-connect/projects/3)

### Milestone 1
The Cram Connect system has been deployed to Galaxy. We currently have a landing page, as shown below.
![](images/M1/landing.jpg)

### Milestone 2
The Cram Connect system has been deployed to Galaxy. We now have a sign in page, register page, a profile page, a location page, and an add location page as shown below.
![](images/M2/signin.JPG)

![](images/M2/register.JPG)

![](images/M2/editProfile.jpg)

![](images/M2/locationPage.JPG)

![](images/M2/addLocation.jpg)

### Milestone 3
The Cram Connect system was not deployed to Galaxy due to the expiration of the free trial. We have implemented a search page, a favorites page, and a discover page. The add location page has been updated with new inputs. The locations page has been updated with a map feature.  
![](images/M3/search.png)

![](images/M3/favorites.png)

![](images/M3/discover.png)

![](images/M3/addlocation.png)

![](images/M3/location.png)

## Developer Guide
Our developer guide, will guide the developer into downloading, installing, running, and modifying the system.

First step is to download and [install meteor](https://www.meteor.com/install).

Second, go to [https://github.com/cram-connect/cram-connect](https://github.com/cram-connect/cram-connect) and download a copy Cram Connect.

Third, cd into the app/ directory of your local copy of the repo, and install third party libraries with:
```
$ meteor npm install
```
Fourth, once all the libraries are installed the application can be run with:
```
$ meteor npm run start
```
If the system runs with no errors, the application will be available at  [http://localhost:3000]( http://localhost:3000)

### ESLint
You can verify that the code obeys our coding standards by running ESLint over the code in the imports/ directory with:
```
$ meteor npm run lint
```

## Community Feedback
The general community sentiment regarding out website is that the concept and current features implemented are effective. There were mixed reactions in regards to the color palette and the ease-of-use of the website, where some found it confusing to navigate and others found it intuitive. Main criticisms were leveraged towards the filter feature and it's inoperability as well as concerns over the conversion of the website to a mobile device or differing window sizes.

Take a look at some of the responses on this [Google Sheet](https://docs.google.com/spreadsheets/d/1QS23m1Fic11t41OmTutasY6-QqDqSCM_SIn8pZFPwcw/edit?usp=sharing). These responses came from a wide variety of UH Manoa users ranging from music majors to electrical/computer engineers! From 5 responses, our web application was given an average rating of 8.2 out of 10!

## Meet the Development Team
* [Marionne Casipit](https://marionne.github.io/)

<p align="center">
   <img src="images/dev/marionne.jpg" width="150" height="150"><br>
   Marionne Casipit is an undergraduate at the University of Hawaii at Manoa pursuing a Bachelor's in Computer Engineering, expected to graduate in the Spring of 2020.
</p>

* [Willy Chang](https://willychangx.github.io/)

<p align="center">
   <img src="images/dev/willy.jpg" width="150" height="150"><br>
   Willy Chang is an undergraduate at the University of Hawaii at Manoa pursuing a Bachelor's in Computer Engineering, expected to graduate in the Spring of 2021.
</p>


* [Alysha Fujitani](https://alyshafujitani.github.io/)

<p align="center">
   <img src="images/dev/AlyshaFujitani.jpg" width="150" height="150"><br>
   Alysha Fujitani is an undergraduate at the University of Hawaii at Manoa pursuing a Bachelor's in Computer Engineering, expected to graduate in the Spring of 2020.
</p>

* [Matthew Sahara](https://saharama.github.io/)

<p align="center">
   <img src="images/dev/matt.jpg" width="150" height="150"><br>
   Matthew Sahara is an undergraduate at the University of Hawaii at Manoa pursuing a Bachelor's in Electrical Engineering with a focus on Electro-Physics, expected to graduate in the Fall of 2020.
</p>
