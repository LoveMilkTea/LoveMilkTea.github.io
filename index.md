![](images/splash.png)

# Table of Contents

* [Inspiration](#Inspiration)
* [What it Does](#what-it-does)
  * [Authentication](#authentication)
  * [Authorization](#authorization)
* [Application Structure](#application-structure)
* [Development History](#development-history)
    * [Hawaii Annual Code Challenge 2017](#hacc17)
    * [Milestone 1: Mockup Development](#milestone-1-mockup-development)
    * [Milestone 2: User Feedback Driven Development](#milestone-2-data-model-development)
* [Contributors](#Contributors)

## Inspiration

As students of the University of Hawai'i at Mānoa we understand the difficulties of finding one's way around on campus.  Whether you're a new student, visitor, established student, or even a faculty member, everyone gets lost on this campus at some point and time, and this can be frustrating.  This issue really struck us as something we wanted to help solve, since we as both students and developers could definitely relate to it, and hope to make navigating at Mānoa an easier experience.

## What it Does

This app helps users explore and also find his or her way around the University of Hawai'i at Mānoa.  This can be done both by searching or filtering by types of points of interest.  Upon selecting a destination, users are able to find more information about it and receive directions.  Users can use Street View and see where a specific location is, and what it looks like, thanks to the tags we've added in this setting.  

We believe that crowdsourcing and collaboration is a powerful and prevalent way to keep information up to date today.  With this in mind, users are also able to add points of interest by submitting their current location, or selecting a specific location manually.  User input can be administratively reviewed for validity.
 
## Application Structure

We built this application using Ionic, which is a cross-platfrom HTML framework.  This means that it is built for use as a web app, as well as for iOS and Android enabled devices.


## Developer Guide

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

### Overview
We used [Ionic](https://ionicframework.com/), [Cordova](https://cordova.apache.org/), and [Firebase](https://firebase.google.com/) to create the app.

### Live Deployment
Check out the live version of our app on your phone or computer at [Heroku!](https://lovemilktea.herokuapp.com). Our app was built for mobile first, so please check it our using your phone (Try out the Streetview).

### Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/en/download/)

After installing Node.js, you must install the required global npm packages.

```bash
sudo npm install -g ionic
```

```bash
sudo npm install -g cordova
```

### Quick Start

Clone the Repository
```bash
git clone https://github.com/HACC17/LoveMilkTea.git && cd LoveMilkTea
```
Install Packages
```
npm install
```

From here, you can either

Run it as a Web Application
```
ionic serve
```
Or run as a Mobile Application in Ionic Labs
```
ionic serve --lab
```

### Mobile Installation

Please visit our mobile-friendly deployment on [Heroku](https://lovemilktea.herokuapp.com)





# User Guide

## Download 

Download Ionic View from the [App Store](https://itunes.apple.com/us/app/ionic-view-test-share-ionic-apps/id1271789931) or on [Google Play](https://play.google.com/store/apps/details?id=com.ionicframework.view).

Next, run it, select view app, and enter the code `93627f19`.

From here, select and run the 'LoveMilkTea' app.

<img src="/img/code.jpg" width=500px>

## Browse Points of Interest on the Map

Find various points of interest, including, but not limited to restaurants, restrooms, entertainment venues, and more.  Further details such as descriptions, hours and the specific address are provided.

<img src="/img/01.png">
<img src="/img/paradise-palms-marker_iphone7plussilver_portrait.png">

## Explore

<img src="/img/06.png">

## Filter Points of Interest

![](images/splash.png)
![](images/splash.png)

## Toggle Your Location

<img src="/img/02.png">

## Get Directions 
Find and map a route to your desired location.

<img src="/img/paradise-palms-route_iphone7plussilver_portrait.png">

## Find Destinations with Street View
Switch to Street View to get a better idea of where your destination is with tags.

<img src="/img/paradise-palms-street-view_iphone7plussilver_portrait.png">
<img src="/img/qlc-street-view_iphone7plussilver_portrait.png">

## Give & View Feedback
Add and browse reviews of any point of interest.

<img src="/img/paradise-palms-info_iphone7plussilver_portrait.png">

## Submit New Points of Interest

We believe in crowd-sourcing. If you notice something missing on the map, add or remove it!

<img src="/img/10.png">
<img src="/img/09.png">
<img src="/img/03.png">
<img src="/img/04.png">


## Administration

Administrators can review, accept or reject data submissions.

<img src="/img/05.png">

Administrative credentials are necessary to utilize functions that allow an administrator to approve, modify or reject user-submitted data.  For the purposes of the HACC of 2017, please contact danny_tan on the Slack to obtain said credentials.


## Contributors

LoveMilkTea was made with love, milk and tea, by LoveMilkTea, which includes the following members:

  * [Tyler Chong](#)
  * [Brendt McFeeley](#)
  * [Shaziney Natividad](#)
  * [Christopher Nguyen](#)
  * [Russell Omo](#)
  * [Chaselyn Pugh](#)
  * [Danny Tan](#)
