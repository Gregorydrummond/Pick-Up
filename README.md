Original App Design Project - README Template
===

# Pick Up

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Organize and join local pickup basketball games. 

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Social / Community / Sports
- **Mobile:** This app is primarily developed for mobile devices but would be almost as functional on computers/laptops. The only downside as of now would be finding more local games depending on location. A non-mobile setup would have a limited opton of games to choose from.
- **Story:** Based on user's location, populate user's feed with locally created  games started by other users of the app.
- **Market:** Targeted to anyone who wants to play pickup basketball      games.
- **Habit:** This app can be useed whenever the user has free time and wants to get active.
- **Scope:** First, we'll allow users to see nearby games. Then, we could start accepting stats and highlights to showcase on the app. Maybe in the future, the app could organize local leagues between multiple user/app created teams.
## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can register for a new account
* User can login/logout
* User can see list/grid view of current local games
* User can create new game
* User can close game (The starter of said game)
* User can end a game (The starter of said game)
* User can see game details for selected game

**Optional Nice-to-have Stories**

* User can tell when a game is full
* User can rsvp/call next 
* User can self report and view stats
* User can edit local distance

### 2. Screen Archetypes
* Login - User logs into their account
    * User can login
* Register - User signs up for their account
    * User can register for a new account
* Stream - User can scroll through important resources in a list
    * User can see list/grid view of current local games
* Detail - User can view the specifics of a particular resource
    * User can see game details for selected game 
* Creation - User can create a new resource
    * User can create new game
* Profile - User can view their identity and stats
    * User can self report and view stats 
* Settings - User can configure app options
    * User can edit local distance (Optional)


### 3. Navigation

**Tab Navigation** (Tab to Screen)
* Initial Screen
    * Login/SignUp
* Main Screen
    * Stream
    * Profile
    * Search?

**Flow Navigation** (Screen to Screen)

* Login
   * Stream
* Register
   * Stream
* Stream
   * Creation
* Detail
   * Stream
* Creation
   * Stream (After creating game)
* Profile
   * Settings
* Settings
    * Profile

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="Pickup Wirefrmae.jpg" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
