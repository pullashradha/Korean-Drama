# Korean Drama

#### Intro Course Team Project for Epicodus, 06/24/2016

#### By Brett New, Halle Williams, Alan Denison & Shradha Pulla

## Description

This program is a choose-your-own-adventure style web game. The user will enter their name and other information to start. Players will navigate through a series of story points, and the program will decide what the ending will be based on the decisions made by the player. This plot of this program is inspired by Korean TV dramas.

## Setup/Installation Requirements

This program can only be accessed on a computer with Git and Atom installed.

* Clone this repository
* Open index.html in Terminal

## Known Bugs

No known bugs.

## Specifications

The program should... | Example Input | Example Output
----- | ----- | -----
Input the player's name and display it in the story | Enter Your Name: Jane | "Hi Jane!"
Input the player's pet's name and display it periodically in the story | What's your pet's name: Charlotte | "Today you and Charlotte, your dog..."
Output specific sentences in the story based on the pet selected at the start | Choose your pet: Dog | "Media Frenzy" page adds the sentence "your dog barks enthusiastically at your side"
Lead to one result based on the radio button selected on the last decision page of the game | Input: radio button 2, checked on "Media Frenzy" page| Output: "Double Dead-End" result page is shown
Lead to another decision page depending on the radio button selected in the current decision page | Input: radio button 1, checked on "Journey Begins" page | Output: "Media Frenzy" page is shown
Lead to different decision pages depending on the special item chosen on the "Journey Begins" page | Input: locket and radio button 2, checked on page "Time Warp" | Output: "Lock(et) Down the Dynasty" result page is shown
Display the player's name, pet's name and a picture of the special item on the side bar | --- | ---
Display a facial expression icon depending on the content of the page, in the side bar | --- | ---
Track what results have been completed and output them in the sidebar if the game is continued (without refreshing the page)| Try Again button clicked by player on "Shark Week" page | Sidebar: "You have seen 1 of 9 possible endings"
Play specific music tracks depending on the current page | Player clicks on "Enter Your Name" input field on the landing page | dangerousLove music clip is played

## Future Features

HTML | CSS | JavaScript
----- | ----- | -----
Add more storylines | Modify the icons on the sidebar to be uniform & look like a video game | Refactor code to be less repetitive when displaying paths-possibly have just one button appear on every page and gather the placement in the storyline based off the radio buttons clicked
Add more game items to modify story | Match the intro form background to the picture on the landing page | Track and list the titles of the ending pages completed instead of just the number
--- | Add in better resolution pictures | Smooth out the audio transitions

## Support and Contact Details

Contact Epicodus for support in running this program.

## Technologies Used

* HTML
* CSS
* Bootstrap
* jQuery
* JavaScript

## Links

Git Hub Webpage: https://pullashradha.github.io/KoreanDrama

### License

*This software is licensed under the GPL license.*

Copyright (c) 2016 Brett New, Halle Williams, Alan Denison & Shradha Pulla
