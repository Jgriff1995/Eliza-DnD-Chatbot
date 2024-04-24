# Final Term Project CSCI-4322-B

### Eliza Dungeons & Dragons AI Chatbot

<img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/echo.jpg?raw=true" align="right"
     alt="Size Limit logo by Anton Lovchikov" width="200" height="200">

### <ins>Introduction<ins>
<p>The purpose of our website is to house an AI chatbot which is a spinoff of the original Eliza chatbot that dates back to 1967. In our modified version of Eliza,
 she acts as a Dungeon Master for the hit table top game Dungeons & Dragons. We are using a GPT powered API to facilitate the game walkthough.</p>

<p>The site is written in vanilla JS using the Node.js framework, while also utilizing HTML/CSS elements. </p>
<p>The AI API is provided through ChatGPT, AI Assistant.</p>


## Table of Contents
- [Introduction](#introduction)
- [Team ECHO Members](#team-echo-members)
- [Setup](#setup)
  - [Default Setup](#default-setup)
  - [Using Nodemon (Optional)](#using-nodemon-optional)
  - [Api Key Setup](#api-key-setup)
- [Site Guide](#site-guide)
  - [Landing Page](#landing-page)
  - [Build Game Page](#build-game-page)
    - [Modal Steps](#modal-steps)
  - [Play Game Page](#play-game-page)
    - [Gameplay](#example)
    - [Error Handling and Misc](#error-handling-and-misc) 

<br>

## Team ECHO Members 
 _James Griffiths_ <br>
 _Gordon Chicowlas_ <br>
 _Emanuel Ortiz_ <br>
 _Tim McCarty_ <br>
 _Nick Landers_ <br>

## SETUP

### <ins>Default Setup<ins>
1. **npm install**

<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/step1.png?raw=true" alt="Size Limit CLI" width="738">
</p>

2. **node app.js**

<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/step2.png?raw=true" alt="Size Limit CLI" width="738">
</p>

3. **Navigate to http://localhost:3050/index.html**

<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/step3.png?raw=true" alt="Size Limit CLI" width="738">
</p>


### <ins>Using nodemon (Optional)<ins>

1. **npm install -g nodemon**

<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/optional1.png?raw=true" width="738">
</p>

2. **npm config get prefix**
   
<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/optional2.png?raw=true" width="738">
</p>

3. **Update System PATH settings**
 
     1. Press the Windows key.
     2. Type "Path" in the search box and select "Edit the system environment variables"
     3. Click on "Environment Variables" near the bottom.
     4. In the "System Variables" section double click on the "Path" variable.
     5. Click "New" on the right-hand side.
     6. Copy and paste this into the box (replace [Username]):
     7. restart your terminal and VSCode.      
  
<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/path.png?raw=true" width="500">
</p>


4. **Add script in Package.JSON**

<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/scriptupdate.png?raw=true" width="400">
</p>

5. **npm run watch**

<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/optional3.png?raw=true" width="738">
</p>

### <ins>Api Key Setup<ins>
1. Navigate to Chat.html (After installing all necessary modules)

2. hit CTRL + F > Search for "YOUR_API_KEY_HERE"

3. Copy + Paste your API_KEY into that area, to properly connect the API to GPT 3.5.


# Site Guide

## Landing Page
<p>When the page loads, you are greeted with a brief description of the purpose of the website, and an image of our Eliza Dungeon Master. </p>
<p>Click the "Build A Game Now" button to be redirected to the "Build Game" Page.</p>

<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/landingImages/home.png?raw=true" width="400">
</p>

## Build Game Page
<p>The build game page will guide you through the process of setting up a D&D campaign. There are a series of 9 modals that allow you to choose the various attributes.</p>


### <ins>Modal Steps<ins>
1. **Welcome / Name input**

<p align="left">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/buildGameImages/modal1.png?raw=true" width="400">
</p>

2. **Race input**

<p align="left">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/buildGameImages/modal2.png?raw=true" width="400">
</p>

3. **Class input**

<p align="left">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/buildGameImages/modal3.png?raw=true" width="400">
</p>

4. **Campaign Length input**

<p align="left">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/buildGameImages/modal4.png?raw=true" width="400">
</p>

5. **Setting input**

<p align="left">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/buildGameImages/modal5.png?raw=true" width="400">
</p>

6. **Tone input**

<p align="left">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/buildGameImages/modal6.png?raw=true" width="400">
</p>

7. **NPC companion count input**

<p align="left">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/buildGameImages/modal7.png?raw=true" width="400">
</p>

8. **Experience level input**

<p align="left">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/buildGameImages/modal8.png?raw=true" width="400">
</p>

9. **Confirmation**

<p align="left">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/buildGameImages/modal9.png?raw=true" width="400">
</p>

10. **Error Checking**
<p>There is a check at each step to ensure the user has actually chosen an option. A default image of a question mark is displayed as placeholder until the user begins choosing options</p>

<p align="left">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/buildGameImages/errorCheckingAlert.png?raw=true" width="400">
</p>

## Play Game Page
<p>Based on the input given in the game building phase, a string is constructed with the user's relevant information, which is sent to the GPT API after the "Build Campaign" button is pressed on the confirmation Modal.
This automatically redirects the user to the Play Game Page. Where they are greeted with a message from Eliza going over the setting and encouraging the user to begin their adventure.</p>

<p>The chatbox is styled after apple's iMessage format, as seen in the picture below</p>

### <ins>Example<ins>

1. **Immediately after clicking "Build Campaign" this is what shows up in the chat page**

<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/playGameImages/chat1.png?raw=true" width="400">
</p>

2. **Continue to respond to the bot, with the different options given.**

<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/playGameImages/chat2.png?raw=true" width="400">
</p>

### <ins>Error Handling and Misc<ins>

1. **If you attempt to load the chat page without first filling out the build game page, you will be met with an error:**

<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/playGameImages/emptyCampaignDetailsModalPopup.png?raw=true" width="400">
</p>

2. **There is an option to clear the campaign and restart, which will clear the campaign details and redirect you to the build game page**

<p align="center">
  <img src="https://github.com/Jgriff1995/Modern-Software-Term-Project/blob/main/public/assets/images/readmeImages/playGameImages/clearOptionModalPopup.png?raw=true" width="400">
</p>


