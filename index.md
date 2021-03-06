## Table of contents

* [Overview](#overview)
* [Goals](#goals)
* [Mockup Pages](#mockup-pages)
* [Use Cases](#use-cases)
* [Extra Sauce](#extra-sauce)
* [Team Members](#team-members)
* [Links](#links)

## Overview
The problem: ICS students often spend more time than they need on their homework and don’t learn the material as effectively as they could, because they study alone and do not leverage the power of face-to-face study groups with peer mentors.

The solution: Link Up Manoa is an application for UHM ICS students to self-organize face-to-face study groups around a course and/or specific homework or project topic.

## Goals

* Use an IDE (IntelliJ IDEA) effectively
* Competent with elementary Javascript
* Use configuration management tools and techniques effectively
* Create high quality technical essays
* Efficiently create software that conforms to standards
* Design and implement web pages using HTML and CSS
* Design using Meteor Framework
* Practice simple project planning techniques
* Write useful project documentation

## Approach

To use Link Up Manoa, a student must login and set up their profile. The profile enables each student to list courses they have taken and for which they are willing to attempt to provide help (sensei), and courses they are currently taking and for which they might need help (grasshopper). Thus, all students are sensei in some courses and grasshoppers in other courses. Each student must also provide a head shot so that they can be visually identified.
Another section of the site lists all of the ICS courses. Within each course, it is possible to see the grasshoppers and the senseis. A grasshopper can propose a study session around a topic currently being covered in their course (for example, “Write my essay on configuration management”, and a time to meet within ICSpace (i.e. 8:30-9:30pm tonight)). This proposal generates a notification to all of the grasshoppers and senseis, and they can respond by saying they intend to come at some point during the time period.
There is an online calendar that shows all of the study sessions and who is attending.
There are two styles of use for Link Up Manoa:

1. You want to plan a group study session for later in the day or some subsequent day. In that case, you schedule the time period for sometime in the future.
2. You are having a problem right now. In that case, you can go into Link Up Manoa and schedule the session for “Right Now!”. This indicates you are right now in ICSpace and need help. All the other sensei and grasshoppers for that course will be notified, and hopefully a group will spontaneously form in a few minutes.

Link Up Manoa seems great in theory, but there is a significant barrier to adoption: students are naturally inhibited about asking for or offering help. This might be overcome through the use of well designed game mechanics.
Part of the design of Link Up Manoa should be some kind of point system, or “levels”, or some other game mechanic to reward students for participating.
In addition, you can solicit gift cards or other kinds of rewards from the ICS Department or UH Manoa to reward the “best” sensei and grasshoppers in a given week, month, or semester. The challenge is to design the point system so that students cannot “game” the system to obtain points without actually helping others. You also want to prevent a “hui” of students from simply pretending to work together to get the most points and then split the prize without actually helping each other.
There must also be admins who monitor the site and who users can contact if they suspect inappropriate behavior.
Important design goals for Study Buddy are:

* To encourage use of ICSpace among ICS students
* Minimize risk of inappropriate encounters by requiring all meetings to occur in ICSpace.
* Encourage face-to-face interaction among ICS students.

There are other mechanisms (Slack, Piazza) for asynchronous, online help and support. Link Up Manoa is designed to facilitate live, real-world help using ICSpace.

## Mockup Pages

Some possible mockup pages include:

* Landing page

This is the general page where all users who first come to our app will see what our app is about and what it does.  It gives a brief explanation to how it works and what to expect.

<img src="images/lum-home.png">

* Login Page

This is the login page that allows new users to create an account with us or returning users to sign in to their account.

<img src="images/lum-login.png">

* Admin home page

Admin homepage is the same functions as the user home pages, but it will have all of the users in an extra tab no matter who the owner. 

<img src="images/lum-admin.png">

* User profile page

The user profile page is where you will see you own profile and information.  

<img src="images/lum-user-page.png">

* Reminder page

The reminder page allows the user to access the study sessions he or she has coming up.  He or she is allowed to approve or decline the study session to ask as an RSVP.  It also allows the user to add time stamped notes to the session if there is any last minute ideas of comments the user wants to put.  On the bottom, the user can add in reminders and check them off as they go.  

<img src="images/lum-reminders.png">

* Register user page

This page will allow the user to register their new account and/or make a new one, if they lost their crudentials.

<img src="images/lum-register-user.png">

* Friends Page


The friends page allows the user to see who their friends are, who is still pending their friend request, and who has requested to be their friend.  On the left side, the user is shown recommendations based on the user's major and classes.  Finally, on the bottom, the user can search for a friends username as well to connect and send a pending request.  

<img src="images/lum-friends.png">

* Tutor Search

The tutor search page lets the user search for tutors in the system.  It shows what their specialties are as well as what classes or subjects they teach.  It also shows their ratings, gives the user a link to their profile, and it allows the user to request the tutor.

<img src="images/lum-tutors.png">

## Data Model

Our data model explains how our back-end of the system will work.  On the left is the User profile schema that we used to create different users.  The user is connected to the friends system.  Then it goes to the classes and study groups.  The system tries to organize your study groups by comparing others to the user's major and classes.  

<img src="images/dataModel.png">

## Use Cases

Whether or not the following bullet points list all pages or not, the completed use case should show an end-to-end scenario of using the system.

* New user goes to landing page, logs in, gets home page, sets up profile. (How do they learn how system works?)
* Admin goes to landing page, logs in, gets home page, edits site.
* User goes to landing page, logs in, requests study sesh.
* User is notified of study sesh, responds. (Can they respond via text message?)
* User checks their status with respect to game mechanics.

## Extra Sauce

After implementing the basic functionality, here are ideas for more advanced features:

* Login using UH CAS to guarantee that all users are UH students.
* Text message interface. See notifications, and reply to confirm attendance all through text message.
* Slack integration to facilitate notification and organization of meetings.
* A Slack Bot to suggest and help implement Study Buddy meetings.
* A rating system for meetings and sensei participation.

## Team Members
* Aubrie Usui
* Kameron Wong
* Jatin Pandya
* Taylor Gabatino

## Links
* <a href="http://linkupmanoa.meteorapp.com/#/">Deployed Page<a/> 
* <a href="https://github.com/link-up-manoa/link-up-manoa/projects/1">Project Milestone 1<a/> 
* <a href="https://github.com/link-up-manoa/link-up-manoa/projects/2">Project Milestone 2<a/> 
* <a href="https://github.com/link-up-manoa/link-up-manoa/projects/3">Project Milestone 3<a/> 
