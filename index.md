<img src='https://github.com/coping-with-covid/coping-with-covid/workflows/ci-meteor-application-template-react/badge.svg'>
## Table of contents

* [Team Members](#team-members)
* [Overview](#overview)
* [Approach](#approach)
* [Use case ideas](#use-case-ideas)
* [Development History](#development-history)
* [Continuous Integration](#continuous-integration)
* [User Guide](#user-guide)
* [More Advanced Ideas](#more-advanced-ideas)
* [Developer guide](#developer-guide)
* [Contact Us](#contact-us)

## Related URLs

- <a href="https://copingwithpandemic.xyz/#/">Deployment of the project</a>

- <a href="https://github.com/coping-with-covid">GitHub organization for the project</a>

- <a href="http://143.110.232.78/#/">Coping with COVID Landing page</a>

- <a href="https://github.com/coping-with-covid/coping-with-covid/projects/1">Milestone 1 page</a>

- <a href="https://github.com/coping-with-covid/coping-with-covid/projects/3">Milestone 2 page</a>

- <a href="https://github.com/coping-with-covid/coping-with-covid/projects/4">Milestone 3 page</a>

## Team Members

- Chris Dang
- Chak Hon Lam
- Guanhong Li
- Li Liang

## Overview

Problem: Student mental health in higher education has been an increasing concern. The COVID-19 pandemic has negatively affected everybody, causing a lot of pressure, uneasiness, despondency, and inner issues for the understudies alongside their companions and their family.

Solution: We propose to create a mental health chat bot that can give students ease and comfort. Making therapy and relief accessible to all. It will be a safe space where people can openly express themselves without fear of judgment.

## Approach

We want to help students reach out during the COVID-19 pandemic and to cope with the distressing issues they are facing. Students will use the site to vent/talk about their day. To accomplish this, our site would suggest a daily topic and users could discuss and share their thoughts around the topic for the day. We would identify keywords students uses in their post and sent out automatic replies that suggest articles or videos that would help comfort the student and make them feel better.

- Daily discussion Page
- User home page
- FAQ page
- Admin home page
- User profile page

## Use case ideas

- New user goes to landing page, logs in, gets home page, sets up profile.
- The Admin goes to landing page, logs in, gets home page, can edit site and update posts.
- User goes to landing page, logs in, get to home page and goes to Daily Discussion Page to post posts.

## Development History

### Inital Idea

Our original idea for the site was to develop a chat bot that could chat and comfort the user.
How the bot would work would be:

- the bot will prompt a topic for conversation.
  - Ex: “ Pineapple on Pizza? Yay! Or Nay?
- Using follow-ups to facilitate responses.
  - The chat bot will identify keywords students use to suggest articles or videos on how to help comfort the student better.

We decided against the chat bot, because we do not have the skill to make the chat bot be interactive enough that it feels "human". The chat function would be too simple and robotic for the user to feel comfort, which defeats the purpose.

### Milestone 1

- Deployed project to digit ocean
<img src="doc/1.PNG">
<a href="http://143.110.232.78/#/">Coping with COVID Landing page</a>

- Inspect MongoDB

<img src="doc/3.png">

- Monitoring the application performance

<img src="doc/2.PNG">

- Mockup pages
<img src="doc/7.png">

<img src="doc/4.png">

<img src="doc/5.png">

<img src="doc/6.png">

<img src="doc/profile.png">

- Active pages
[Landing Page](http://143.110.232.78/#/)
<img src="doc/landingfaq.jpg">

[Sign In Page](http://143.110.232.78/#/signin)
<img src="doc/login.JPG">

[Sign Up Page](http://143.110.232.78/#/signup)
<img src="doc/signup.JPG">

[Profile Page](http://143.110.232.78/#/profile)
<img src="doc/profilepage.JPG">

[Edit Profile Page](http://143.110.232.78/#/profile)
<img src="doc/editprofile.JPG">

### Milestone 2

- [Lnding Page](https://copingwithpandemic.xyz/#/)
<img src="doc/landing.2.PNG">

- [Signin Page](https://copingwithpandemic.xyz/#/signin)
<img src="doc/login.2.PNG">

- [SignUp Page](https://copingwithpandemic.xyz/#/signup)
<img src="doc/signup.2.PNG">

- [Home Page]()

- [Forum Page]()

- [COVID-19 Website](https://copingwithpandemic.xyz/#/websites)
<img src="doc/web.2.PNG">

- [FAQ Page]()


- [Profile](https://copingwithpandemic.xyz/#/profile/)
<img src="doc/profile.2.PNG">

- [Updata Profile](https://copingwithpandemic.xyz/#/editprofile/)
<img src="doc/updata.2.PNG">


## User Guide

## Continuous Integration

## More Advanced Ideas

We are unsure how this can be implemented but down below is ideas we hope can improve the app:
  - Direct access to professionals that can assist student’s mental state
    - It be cool with this could somehow connect with UH’s counseling center
  - Somehow per user have old messages saved. So user can look back at them.
  - Daily check in
    - Ex: Mood Tracker, but there can be a calender will user can see logged mood.

## Developer Guide

### Installation

First, install [Meteor](https://www.meteor.com/install).

Second, download a copy of coping-with-covid.

Third, cd into the app directory and install the required libraries with:
````$ meteor npm install````
Once the libraries are installed, you can run the app by invoking:
````$ meteor npm run start````
The first time you run the app, it will create some default users and profiles.
You can safely ignore the bcrypt warning.
If all goes well, Coping with COVID will appear at http://localhost:3000/. You can login using the credentials in settings.development.json, or else register a new account.

## Contact Us
- Chris Dang

Email: cdang808@hawaii.edu
- Chak Hon Lam

Email: chakhon@hawaii.edu
- Guanhong Li

Email: guanhong@hawaii.edu
- Li Liang

Email: liangli@hawaii.edu
