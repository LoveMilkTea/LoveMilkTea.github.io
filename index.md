![Splash Image](images/splash.png)

# Table of Contents

* [Inspiration](#inspiration)
* [What it Does](#what-it-does)
  * [Browse](#browse)
  * [Explore](#explore)
  * [Filter](#filter)
  * [Get Directions](#get-directions)
  * [Find Destinations with Street View](#find-destinations-with-augmented-reality)
  * [Give & View Feedback](#give--view-feedback)
  * [Submit New Points of Interest](#submit-new-points-of-interest)
  * [Administration](#administration)
* [Application Structure](#application-structure)
* [Download](#download)
* [Development History](#development-history)
    * [Milestone 1: Mockup Development](#milestone-1-clean-code-and-looking-forward)
    * [Milestone 2: Data Model Development](#milestone-2-finalizing-development)
* [Contributors](#contributors)

## Inspiration

As students of the University of Hawai'i at Mānoa we understand the difficulties of finding one's way around on campus.  Whether you're a new student, visitor, established student, or even a faculty member, everyone gets lost on this campus at some point and time, and this can be frustrating.  This issue really struck us as something we wanted to help solve, since we as both students and developers could definitely relate to it, and hope to make navigating at Mānoa an easier experience.

## What it Does

This app helps users explore and also find his or her way around the University of Hawai'i at Mānoa.  This can be done both by searching or filtering by types of points of interest.  Upon selecting a destination, users are able to find more information about it and receive directions.  Users can use Street View and see where a specific location is, and what it looks like, thanks to the tags we've added in this setting.

We believe that crowdsourcing and collaboration is a powerful and prevalent way to keep information up to date today.  With this in mind, users are also able to add points of interest by submitting their current location, or selecting a specific location manually.  User input can be administratively reviewed for validity.

### Browse

Browse for various points of interest, including, but not limited to restaurants, restrooms, entertainment venues, and more. When browsing, further details such as descriptions, hours and the specific address are also provided, allowing you to get information about those specific places.

<img src="/images/all.png">
<img src="/images/info.png">

### Explore

Using the "Explore" sidebar item, you can see some of the hottest places on campus, including locations such as the Warrior Recreational Center or Campus Center.

<img src="/images/explore.png">

### Filter

If you are looking for something specific, filter by a specific category and find what you want with ease.

<img src="/images/filter1.png">
<img src="/images/filter2.png">

### Get Directions

Directions are available through the app with Google Maps, so you can navigate the campus using the shortest route possible.

<img src="/images/directions.png">

### Find Destinations with Augmented Reality

Switching to Augmented Reality allows you to get a better idea of where your destination is using overlays on top of Google's Stret View.

<img src="/images/street1.png">
<img src="/images/street2.png">

### Give & View Feedback

Write your own and browse through existing reviews of any point of interest.

<img src="/images/feedback.png">

<img src="/images/comments.png">

### Submit New Points of Interest

We believe in crowd-sourcing. If you notice something missing on the map, add it!

<img src="/images/submit0.png">
<img src="/images/submit1.png">
<img src="/images/submit2.png">
<img src="/images/submit3.png">


### Administration

Administrators can review, accept or reject data submissions. Administrative credentials are necessary to utilize functions that allow an administrator to approve, modify or reject user-submitted data.

<img src="/images/approve.png">

User accounts are required for users to comment on places of interest. The user can signup with a valid email and password then confirm their accounts through a link sent to their email. This ensures only valid email accounts are used to create accounts.

<img src="/images/notverified.png">

Here is an example of a confirmation email.

<img src="/images/confirmEmail.png">

## Application Structure

We built this application using Ionic, which is a cross-platform HTML framework. This means that it is built for use as a web app, while simultaneously being built for iOS and Android enabled devices.

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

You can watch this video to see what getting your local installation up and running should look like.

[![asciicast](https://asciinema.org/a/XHDe3NGNNgGQFPSczrT7BUwZ9.png)](https://asciinema.org/a/XHDe3NGNNgGQFPSczrT7BUwZ9)

### Mobile Installation

Please visit our mobile-friendly deployment on [Heroku](https://lovemilktea.herokuapp.com)

Native mobile apps coming soon!

## Download

Download Ionic View from the [App Store](https://itunes.apple.com/us/app/ionic-view-test-share-ionic-apps/id1271789931) or on [Google Play](https://play.google.com/store/apps/details?id=com.ionicframework.view).

Next, run it, select view app, and enter the code `93627f19`.

From here, select and run the 'LoveMilkTea' app.

<img src="/images/code.jpg">

## Development History

### Milestone 1: Clean Code and Looking Forward

During this milestone, we focused on cleaning up our existing code base. Much of the code from the Hawaii Annual Code Challenge was focused towards functionality rather than sustainability. After the code was changed to be more understandable and maintainable, we turned towards improving the application. We improved the styling on various places throughout the app, changed out icons to make it more intuitive, and finished implementing user accounts.

### Milestone 2: Finalizing Development

Milestone 2 was about continuing the issues left in Milestone 1, as well as updating and adding anything we felt needed to be added. During this milestone, we improved the administrative part of our app, allowing administrators to more easily manage incoming submissions and existing data. We also added supporting events happening as apart of our app, as well as deploying our app to the Google Play Store. 

## Contributors

Wayfinder was made with ❤️ and Milk Tea ☕, by team LoveMilkTea, which includes the following members:

  * [Tyler Chong](https://github.com/Viltaria)
  * [Brendt McFeeley](https://github.com/brendtmcfeeley)
  * [Shaziney Natividad](https://github.com/shaziney)
  * [Christopher Nguyen](https://github.com/chrisnguyenhi)
  * [Russell Omo](https://github.com/russellomo)
  * [Chaselyn Pugh](https://github.com/cepugh)
  * [Danny Tan](https://github.com/dannytan)
