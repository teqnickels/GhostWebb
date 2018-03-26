# Project Overview

 GhostWeb is a React based web application that allows users to record messages via the GhostWeb application, store those messages, and access those and other messages from the locations in which they were recorded. This is a learning project I am doing while attending The Learner's Guild. My goal is to learn: 
    - React
    - Redux
    - How to build a full stack React project 
    - OAuth
    - To work with Google's API
    - Find out what exists that allows me to work with the Google API and React
    - How to store audio clips in a database
    
  ### Features:
  - [ ]  Users can log in via Google OAuth
  - [ ]  User must be logged in to see any other features
  - [ ]  Users can see all audio clips on the Google map
  - [ ]  When user scrolls out in Google maps, audio clips closely located will [cluster together](https://developers.Google.com/maps/documentation/javascript/marker-clustering)
  - [ ]  Users can listen to an audio clip only when they are within a small radius to the audio clip
  - [ ]  Users can record an audio clip to the app
  - [ ]  When a user records an audio clip, the clip is assigned coordinates according to the location of the user
  - [ ]  Users can listen to audio clips from other users
  - [ ]  Users can listen to their own audio clips

  ##### Optional Features:
  - [ ]  Users have the option to see just their audio clips on google maps
  - [ ]  Users can follow other users
  - [ ]  Users can select categories to file their audio clips under
  - [ ]  Users can select a category to filter audio clips
  - [ ]  Users can upload a profile picture, bio, and simple updates (like "I will be traveling to --location-- next!" or "The next museum tour will be at --location--")
  - [ ]  When a user is near an audio clip(s), they receive a notification with the option to play clip

  ##### Tech stack for this project:
  - [ ]  React Native
  - [ ]  PostgreSQL
  - [ ]  Node.js
  - [ ]  Express
  - [ ]  Mocha
  - [ ]  Chai
  - [ ]  OAuth
  - [ ]  Flexbox
  - [ ]  Google Maps API
  - [ ]  Audio modules

  Interested in learning [Redux](https://www.udemy.com/react-redux/)?

# Configuration Instructions
  
# Installation Instructions
_Visit: https://github.com/teqnickels/GhostWebb/wiki/Installation-Instructions and follow installation the installation   instructions_
# Operating Instructions

# File Structure
```
app
  ├── index.html
  ├── package-lock.json
  ├── package.json
  ├── src
  │   ├── actions
  │   │   └── index.js
  │   ├── components
  │   │   ├── App.js
  │   │   └── MapContainer.js
  │   ├── config.js
  │   ├── containers
  │   ├── data
  │   │   └── markersData.json
  │   ├── index.js
  │   └── reducers
  │       └── index.js
  ├── style
  │   └── style.css
  ├── test
  │   ├── components
  │   │   └── app_test.js
  │   └── test_helper.js
  └── webpack.config.js
```
   
# Licensing
 MIT License

# Known Bugs
 This project is currently unfinished. To do items are listed unchecked in the changelog in this document. 
 
# Credits and Acknowledgments
 This project is the creation of https://github.com/HJBowers and we paired on the project prior to this fork. 
 
# Changelog
- [ ] Build out React scaffolding
  - [x] App Component
  - [x] Map Component
  - [ ] Markers Component
  - [ ] Recorder Component
  - [ ] Login Component
  - [ ] Signup Component
  - [ ] Profile Component
  - [ ] Search Component
- [ ] Implement Google Maps API
  - [ ] Implement Google Places
  - [ ] Default Location (If no location can be retrieved from user) should be in Oakland, CA. 
  
# News


