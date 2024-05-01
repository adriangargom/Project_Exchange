# Project Exchange

### Table of contents 
1. [Project Description](#project-description)
2. [Technologies](#technologies)
3. [Features](#features)
4. [User Roles](#user-roles)

<br/>

## Project Description

The following project consists of a native Android application to exchange items from various categories,
designed with the promise of being simple to use and practical for beginner or casual users.

<br/>

## Technologies

In this case we have been developing the project for Android so we have been using the Android Studio
IDE as the base tool for working in this project and for developing the application natively for this OS.

Also, we have been using the following Firebase services for managing critical parts of the application:

- Firebase Authentication: This service has been useful for managing all the user accounts and authentication
methods inside our application.

- Firebase Firestore: We have been using this service as NoSQL database for storing all the necessary data inside of
our application.

- Firebase Storage: Finally, this service has been used for storing all the image resources from our application.

So finally, the used technologies are the following ones:


| Field             | Technology            |
|:------------------|:----------------------|
|Languages          |![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)|
|Libraries          |![Jetpack Compose](https://img.shields.io/badge/-Jetpack%20Compose-darkgreen?style=for-the-badge&logo=android&logoColor=white) ![Dagger Hilt](https://img.shields.io/badge/-Dagger%20Hilt-red?style=for-the-badge&logo=android&logoColor=white) ![Coil](https://img.shields.io/badge/-Coil-blue?style=for-the-badge&logo=android&logoColor=white) ![Mapbox](https://img.shields.io/badge/-Mapbox-black?style=for-the-badge&logo=mapbox&logoColor=white)|
|Database           |![Firebase](https://img.shields.io/badge/-Firebase-darkorange?style=for-the-badge&logo=firebase&logoColor=white)|
|DevOps             |![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Android Studio](https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white)|

<br/>

## Features
As I have previously mentioned, this application allows user from all around the world to exchange 
items that belong to diverse categories, for allowing the users to do that in the application 
covers the following features:

- Sign In and Sign Up: All the users can sign up into a new account by providing the requested data or in the other hand, sign into an existing account.

- Profile Management: A user can manage all his profile and account data.

- Offers Management: The users can view all the available offers, create new ones and delete or update them.

- Map View: The users can view all the offers in the basic list format, or they can opt for viewing all the offers in a global map that allows them to view how close the offer is from them.

- Review offers: A user can view and create new reviews over an existing offer.

- Chat: When a user is interested in one offer, he can start a chat conversation with the offer owner for asking questions about the product or according to how the exchange is going to be performed.

<br/>

## User Roles
The application contains tree principal roles "ADMINISTRATORS", "BASE USERS" and "VISITORS" each one of the roles can perform diverse actions over the application based on the privilege levels.

In the following chart, we can see all available and restricted features for each one of the roles inside the application:

|Feature                                |Visitor User    |Base User          |Administrator User |
|:--------------------------------------|:---------------|:------------------|:------------------|
|Manage his user profile                |❌             |✅                 |✅                |
|Manage the categories                  |❌             |❌                 |✅                |
|View the categories                    |✅             |✅                 |✅                |
|Manage his offers                      |❌             |✅                 |✅                |
|Manage all the offers                  |❌             |❌                 |✅                |
|Create new offer                       |❌             |✅                 |✅                |
|Use the chat system                    |❌             |✅                 |✅                |
|View all the offers in list format     |✅             |✅                 |✅                |
|View all the offers in map format      |✅             |✅                 |✅                |
|Filter offers                          |✅             |✅                 |✅                |
|View offer details                     |✅             |✅                 |✅                |
|View offer reviews                     |❌             |✅                 |✅                |
|Create offer reviews                   |❌             |✅                 |✅                |
|Censor offer reviews                   |❌             |❌                 |✅                |
|Delete offer reviews                   |❌             |❌                 |✅                |
|View the actual offer location         |✅             |✅                 |✅                |