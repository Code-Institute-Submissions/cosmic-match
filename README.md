# Cosmic Match

<div align="center">
    <img src="assets/images/readme/introduction-img.png" alt="Cosmic Match displayed on different devices" >
</div>

Memory games are an entertaining way to improve one's memory, concentration, and attention to detail. Even though it can be as beneficial to small children as to adults, most games are designed for children. 

That's when **Cosmic Match** comes into play. It's a simple memory game that uses star constellations as images to be matched and provides an overall nice feel to the game. Using real star constellation might further enable the player to recognize star constellations in the night sky in real life.

The player is presented with 12 cards turned on their back. When the player clicks on the card, it's front is displayed, which should be memorized by the user to find the matching pairs. Each turn two cards are flipped and either matched or turned back for another try. Goal of the game is to match all cards before the time runs out. 

[Cosmic Match - Live website](https://anabelalealcosta19.github.io/cosmic-match/)


## Table of Content

1. User Experience (UX) 
    - Goals
        - [User](#user)
        - [Developer](#developer)
    - [User Stories](#user-stories)
    - Design Choices
        - [Layout](#layout)
        - [Colour scheme](#colour-scheme)
        - [Images](#images)
        - [Typography](#typography) 
        - [Icons](#icons)
    - [Accessibility](#accessibility)
    - [Navigation](#navigation)
    - [Wireframes](#wireframes)
1. Features 
    - [Existing features](#existing-features)
    - [Future considerations](#future-considerations)
1. Technologies used
    - [Languages](#languages)
    - [Libraries](#libraries)
    - [Tools](#tools)
1. Testing
    - [Code Validation](#code-validation)
    - [Initial Testing](#initial-testing)
    - [Responsiveness](#responsiveness)
    - [Browsers](#browsers)
    - [Functionality testing](#functionality-testing)
    - [Other](#other)
1. [Existing bugs](#existing-bugs)
1. Deployment
    - [Deploy project](#deploy-project)
    - [Deployed vs development version](#deployed-vs-development-version)
    - [Run code locally](#run-code-locally)
1. Credits
    - [Media](#media)
    - [Code](#code) 
    - [Acknowledgments](#acknowledgments)
1. [Disclaimer](#disclaimer)
 
## User Experience (UX)

Generally, Cosmic Match intends to provide a seamless user experience by remembering the users' name and preferences as well as by including different features that enhance the gaming experience. 

Furthermore, it rounds off with his responsive and pleasing design, which is adequate for the targeted audience as well as the overall topic of the website. 

### Goals

#### User

Cosmic match targets the following audience: 
- English speaking
- Age can generally range, although the youngest users are expected to be teenagers
- Diverse audience *(gender, social status, nationality)*, but generally in private/free time
- Slight to strong interest in astrology

User goals: 
- Is looking for entertainment/a time waster 
- Wants to play a simple game with little time commitment
- Wants to play a game that is adequate for his age
- *Possibly looking specifically for a memory game to improve memory and concentration*

Cosmic Match fits these goals as it provides a simple memory game with an adequate design for the users' age. Furthermore, the time commitment to play Cosmic Match is very little as it can be started as soon as the name and difficulty preference have been submitted. For users that come back, this initial step is further condensed as it remembers the users' preferences. Additionally, each round is very short, with the longest taking 1min 15s. 


#### Developer

Developer goals: 
- Create a user friendly and intuitive memory game
- Learn how to write JavaScript to create and combine different functionalities into one consistent project
- Learn how to debug JavaScript effectively
- Write defensive code to ensure that unexpected actions from users don't have a negative effect on the website and overall user experience

### User Stories

- **User 1** ... is a first time-visitor of Cosmic Match
    - I want to be able to quickly start playing without having to create an account
    - I want to be able to choose a difficulty that seems adequate for my first try
    - I want to be able to review instructions on how to play the game
    - I want to be able to pause the game if an external distraction occurs
    - I want to be able to restart the game if I messed up (without having to wait until the time runs up)
    - I want to be able to change my difficulty settings in case I noticed it's too easy/too hard (without having to complete the game)
    - I want to be able to change my name in case it has a typo (without having to complete the game)
    - I want to notice easily when the time runs up
    - I want to have an overview of the current game like difficulty, time and flips without those details being too distracting
    - I want to have appropriate feedback when losing or winning the game 
    - I want to be able to play again if I liked the game

- **User 2** ... played Cosmic Match before
    - I want to be able to quickly start playing without having to enter all my details again
    - I want to be able to pause the game if an external distraction occurs
    - I want to be able to restart the game if I messed up (without having to wait until the time runs up)
    - I want to notice easily when the time runs up
    - I want to have an overview of the current game like difficulty, time and flips without those details being too distracting
    - I want to have appropriate feedback when losing or winning the game 
    - I want to be able to play again if I want

- **User 3** ... saw a friend play Cosmic Match and wants to give it a try himself
    - I want to be able to easily change the name to my own
    - I want to be able to choose a difficulty that seems adequate for my first try
    - I want to be able to review instructions on how to play the game
    - I want to be able to pause the game if an external distraction occurs
    - I want to be able to restart the game if I messed up (without having to wait until the time runs up)
    - I want to be able to change my difficulty settings in case I noticed it's too easy/ to hard (without having to complete the game)
    - I want to be able to change my name in case it has a typo (without having to complete the game)
    - I want to notice easily when the time runs up
    - I want to have an overview of the current game like difficulty, time and flips without those details being too distracting
    - I want to have appropriate feedback when losing or winning the game 
    - I want to be able to play again if I liked the game

### Design Choices

#### Layout

The whole website is visible on the users' screen which ensures that he doesn't have to scroll at any time. This has also been considered when deciding the number of cards as 12 cards can be displayed clearly across all devices while keeping the website on the users' viewport. Like this, all cards, icons and game details are in the users' field of view and are accessible at any moment during the game. 

Last but not least, the layout changes depending on the device size to ensure readability and ease of use. The additional icons also come into play on smaller devices to ensure that the website isn't too busy. 

#### Colour scheme

My colour choices were made with consideration of the background image. 

All the text elements as well as icons are white to provide clear contrast and ensure readability. The gradient colours for the glowing effect were selected in the colour picker in Chrome's DevTools by eye to ensure a visually appealing effect. This was used to additionally highlight specific text elements.

I've selected a dark blue (rgb(10, 22, 30)) for the background of the cards and modals as it fits with the overall background image while still contrasting well. Furthermore, white borders have been used for the cards by default to provide crisp and clear separation. The off-white rgb(248, 249, 250) as border and border shadow has additionally been used to distinguish selected cards from others. The same effect has been used for the modals at it highlights the modal from the faded out background and looks overall visually appealing. This has also been used when hovering over the buttons in the modals to provide the user with immediate feedback that this button is clickable. 

For the last seconds on each round, I've selected rgb(255, 122, 122). It's a soft shade of red that clearly signalizes that the time runs up and fits with the colours of the background image. It, nevertheless, is contrasting to the background and gets the users' attention with ease. 

The red colour rgba(199, 41, 41, 0.8) has been used for the cancel button in the settings modal as it clearly indicates a way out from changing the settings. This has also been used when hovering over the buttons in the modals to provide the user with immediate feedback that this button is clickable.

#### Images

The background image plays a central role as it sets the overall atmosphere of the page. Therefore, several crops of the same image have been made to ensure high quality and good positioning across all devices.

The cards have vectors of star constellations as their front face while their back has a vector of a simple telescope. All selections have been made to fit the topic of Cosmic Match. 

#### Typography

The font **Orbitron** is a geometric sans-serif typeface that has a "spacey" touch to it. It was used for the website's name "Cosmic Match" to give it a brand-like look, which fits the overall topic perfectly. 

The font **Montserrat** was one of the popular pairings with Orbitron suggested by Google fonts. I chose to use this font as it's a very clean font, which gives additional effect to Orbitron. It has been used for all the other text on the website.  

#### Icons 

Icons were used for the action items on the website: pause/resume, restart, instructions, and settings. Their meaning is obvious as commonly used on websites/applications, which allows the user to immediately understand his options without needing to read through any text. Especially since the user is playing a game, this allows him to act quickly without being too distracted. 

Additionally, icons were used for the game details (time, flips, and difficulty level) on mobile devices to give additional space and make the website less busy for the user. 

Last but not least, a trophy icon was used in the congratulations modal to provide the user with a feeling of achievement. 

### Accessibility

The accessibility of websites is an important factor when planning and creating a project. To ensure accessibility, the following points have been implemented:

* **Images:** To ensure that any images provided give additional context to the user, the alt attribute has always been included with a short image description. 
* **Icons:** As icons were not used for decorative purposes but to provide the user with additional information (time, flips and difficulty level on mobile devices) or functionality (pause/resume, restart, open instructions, and change settings), additional information is provided to screen readers only. 

### Navigation

The navigation between the game itself and different modals is mainly controlled by the developer. 

There are two modals, that will show on page load. When the user accesses the website, the JavaScript code checks if he's a first-time user by checking if a player's name has been saved in a previous session. 

If any data can be found, the modal "Repeat start page" is displaying. 

<div align="center">
    <img src="assets/images/readme/repeat-start-page.png" alt="Repeat start page" >
</div>


Should no data be found, the modal "First start page" will show instead. 

<div align="center">
    <img src="assets/images/readme/first-start-page.png" alt="First start page" >
</div>

Once the user sees the main page with the game, he can access the instructions and settings modal through the respective icons. Please see below: 

<div align="center">
    <img src="assets/images/readme/navigation.png" alt="Navigation from the main page" >
</div>

Two further modals are triggered by the JavaScript code: Game over and Congratulations. 

Should the time run out before the user finds all matching pairs, the Game over modal will show.

<div align="center">
    <img src="assets/images/readme/game-over.png" alt="Game over modal" >
</div>

If the user finds all matching pairs, the Congratulations modal will display. 

<div align="center">
    <img src="assets/images/readme/congratulations.png" alt="Congratulations modal" >
</div>

All buttons of the modals, bring the user back to the main page with the memory game. 

### Wireframes

The following wireframes were created using [Balsamiq](https://balsamiq.com/?gclid=CjwKCAjwh472BRAGEiwAvHVfGsly1Nt9bDZCFUTGCc9I8OfaLtSIcxLhm_WX8911ERsm__luBJslTBoCqgQQAvD_BwE) during the design and planning process for this project. They have not been amended since the repository has been created and, therefore, display small differences when compared to the live website.

* [First start page](assets/wireframes/first-start-page.pdf)
* [Memory game](assets/wireframes/memory-game.pdf)
* [Modal - Instructions](assets/wireframes/instructions.pdf)
* [Modal - Game won](assets/wireframes/game-won.pdf)
* [Modal - Game over](assets/wireframes/game-over.pdf)

While writing code, two further modals were added as they would provide an improved user experience. Their wireframes have been created at a later moment. 

* [Repeat start page](assets/wireframes/repeat-start-page.pdf)
* [Modal - Settings](assets/wireframes/settings.pdf)

## Features
 
### Existing Features

- **Functionality executed on page load**
    - When the user loads the page, the code checks if there's a player name stored from a previous session. 
        * No player name is found: first start page modal is displayed and the default difficulty level easy is set.
        * Previous player details are found: display repeat start page modal, update the player name and difficulty button focused in the modal, update player name and difficulty in main page. 

- **First start page modal**
    - When arriving at the page for the first time, this modal pops up to collect the player's name and give him the option to select the desired difficulty level. Please note that the difficulty easy is selected by default. 
    - The input of the player name is required and limited to 10 characters to allow it to be displayed neatly across all devices. 
    - The active/clicked button has distinct styling to clearly indicate to the user which difficulty has been selected. Choosing a different difficulty will simply remove this styling from this button and add it to the newly selected one. 
    - The play now button changes his styling on hover to indicate that it's clickable to the user. 
    - The modal has been programmed to only close when clicking on the "Play now" button - not when clicking outside the modal or pressing enter after typing in the name. This is to ensure that all details have been given and that the needed functionality to set up the game is executed. 
    - Functionality executed upon pressing "Play now": 
        * Store player name and difficulty selected
        * Depending on difficulty: adapt time limit, display difficulty and select cards used
        * Shuffle cards and start timer

<div align="center">
    <img src="assets/images/readme/first-start-page.png" alt="First start page" >
</div>

- **Repeat start page modal**
    - For any subsequent times that the user visits this website, this modal pops up. It has text that indicates that Cosmic Match is aware that it has already been played by the user. Additionally, the modal displays the player's name and difficulty preference from their last session. 
    - The user has the option to change the difficulty. The active/clicked button has distinct styling, which changes if another difficulty is selected.
    - The user can also change the player name by clicking on the link *"You're not [player name]?"*. Upon clicking, a field for the name input opens, which allows the user to update his current player name. Updating the name is optional and limited to 10 characters. Please note that the player name will only be updated if this field isn't empty. 
    - The modal has been programmed to only close when clicking on the "Play now" button - not when clicking outside the modal or pressing enter after typing in the name. This is to ensure that the needed functionality to set up the game is executed. 
    - The play now button changes his styling on hover to indicate that it's clickable. 
    - Functionality executed upon pressing "Play now": 
        * Depending on difficulty selected: adapt time limit, display difficulty and select cards used
        * Check if new player name has been provided and update it accordingly
        * Shuffle cards, start timer and reset flip counter

<div align="center">
    <img src="assets/images/readme/repeat-start-page.png" alt="Repeat start page" >
</div>

- **Main page**
    - The main page consists of 5 sections: Cosmic match title, player name, game details, action items, and the game board with the cards.
    - The player name updates according to the player's input to engage him additionally in the game. 
    - The game details section displays the time the user has left, the flips made and the difficulty selected. It updates automatically to always inform the user of the current state of his game. 
    - The action items are displayed neatly as icons and allow the user to perform additional actions: pause/resume game, restart game, open instructions, and change settings. For all icons, the cursor has been added as a pointer to indicate their clickability.   

<div align="center">
    <img src="assets/images/readme/main-page.png" alt="Main page" >
</div>

- **Game details**
    - **Timer:** The timer displays the time the user has left to complete the game. It is automatically updated depending on the selected difficulty level and is displayed in minutes and seconds. Additionally, it changes the font colour to a soft red when less than 10 seconds are left, to signalize to the user that the time is running up. 
    - **Flips Counter:** The flips counter increases each time the user flips a card and not upon clicking a card. This ensures that cards clicked twice in the same turn are only counted once. 
    - **Difficulty:** It displays the difficulty selected and updates should it be changed.

- **Pause/resume**
    - When clicking on the pause icon, the timer is paused and the event listener is removed from the cards to prevent the user from playing. 
    - Additionally, the pause icon is hidden and the resume icon is displayed instead, to provide the user with the option to continue the game. 
    - When the resume icon is clicked, the timer continues where left off and the cards can be clicked again. At the same time, this icon is exchanged with the original pause icon to bring this functionality to full circle. 

- **Restart**
    - The restart functionality allows the user to restart the current game.
    - Functionality executed once clicked:
        - Flips counter is reset
        - Time is set back to original time-limit (depending on difficulty) and if applied, the red styling for the last seconds is removed. 
        - If the game was paused previously and the user had the option to resume the game, this is replaced by the pause icon and it's functionality.
        - All cards are flipped back and shuffled. Please note that a time out function has been used to ensure that the cards are only shuffled when all cards are fully flipped back. Furthermore, the cards cannot be clicked until those steps are completed to prevent any issues. 

- **Instructions**
    - The question mark icon allows the user to open the game instructions any time during the game. The user can then read through the rules and objective of the game, which should enable him to be successfull. 
    - While the instructions modal is displaying, the timer is paused. Upon clicking it's button, the time resumes where it has left off. 

<div align="center">
    <img src="assets/images/readme/instructions.png" alt="Instructions modal" >
</div>

- **Settings**
    - When clicking on the cog icon, the settings modal is opened. It has one section to amend the player name as well as difficulty. Additionally, it includes two buttons: "Confirm changes" and "Cancel". 
    - The current player name is displayed by default and can be amended as desired by the player. Furthermore, the current difficulty level can be changed by clicking on a different difficulty button. 
    - The modal has been programmed to only close when clicking on the buttons to ensure that their functionality is executed as intended.
    - Functionality executed upon pressing "Confirm changes": 
        * Depending on difficulty selected: adapt time limit, display difficulty and select cards used
        * Shuffle cards, start timer and reset flip counter
        * If the game was paused previously and the resume icon is replaced by the pause icon.
        * Update new player name
    - Functionality executed upon pressing "Cancel": 
        * Close modal and resume timer where left off

<div align="center">
    <img src="assets/images/readme/change-settings.png" alt="Settings modal" >
</div>

- **Game board**
    - The game board displays the cards selected (depending on difficulty). By default, the cards are displayed with their back up. 
    - Upon clicking any card, the card gets flipped with a 3D effect and the user can see the card front. Additional styling of the border of the card is applied to emphasize which card has been selected. Both effects make the memory game more entertaining, which ensures that the user stays engaged with the game.
    - Once the second card is selected, JavaScript code is executed to check if the cards match or not. Please note, that the cards have time to fully flip before any subsequent code is executed. 
        - Cards match: The highlighted border is removed and the cards stay with their front up. The user can now try to match another pair.
        - Cards don't match: The highlighted border is removed and the cards are flipped back. The user can again try to match another pair.
    - While the code for matched/not matched cards is executed, no other cards can be clicked to protect the memory game's logic.
    - Please also note, that a function has been added to prevent cards to be matched with themselves. Should the user click twice on the same card, nothing happens. This forces the user to click on a different card instead.  

- **Congratulations modal**
    - If the player finds all matching pairs, the congratulations modal opens. 
    - The modal congratulates the user for his success and encourages him to play another round. It also gives the option to change the difficulty level before starting a new game. 
    - The modal only closes when clicking on "Play again" to ensure that its functionality is executed.
    - Functionality executed upon pressing "Play again": 
        * Depending on difficulty selected: adapt time limit, display difficulty and select cards used
        * Shuffle cards, start timer and reset flip counter

<div align="center">
    <img src="assets/images/readme/congratulations.png" alt="Congratulations modal" >
</div>

- **Game over modal**
    - Should the time run up before all matching pairs have been found, then the game over modal will show. 
    - The modal gives the user appropriate feedback that he lost and encourages him to play another round. It also gives the option to change the difficulty level before starting a new game. 
    - The modal only closes when clicking on "Play again" to ensure that its functionality is executed.
    - Functionality executed upon pressing "Play again": 
        * Depending on difficulty selected: adapt time limit, display difficulty and select cards used
        * Shuffle cards, start timer and reset flip counter

<div align="center">
    <img src="assets/images/readme/game-over.png" alt="Game over modal" >
</div>


### Future considerations

- **Adding audio to enhance UX**
    - The website should be enhanced with audio effects in the future as this would improve the overall user experience and engage the user more in the game.
    - Appropriate sound effects should be used when clicking on the cards, matching pairs and losing or winning the game. 
    - The sound will be turned on by default, but the user should be presented with an option to toggle it on/off as to his own preference. 
- **Add scoring system**
    - By implementing a scoring system, the user will be more engaged in the game as he tries to improve his personal score. 
    - Both - time and card flips - will be taken into consideration for the score. Matching cards at an earlier stage will score higher points. Furthermore points for the remaining time will be added, as points for the card flips subtracted.
    - The user will further be presented with his personal highscore which will display on the game dashboard and update automatically should he improve himself. 
- **Provide additional information about star constellations**
    - While the player is matching the cards he might ask himself which star constellations he's currently looking at. 
    - The user should have the ability to get more details about each of the star constellation through an magnifying icon in the action items section. Once clicked, it will open a modal that contains the image of each star constellation used, it's name and additional fun facts like e.g. it's overall size. 
    - This will round up the experience for the user and prevent him to leave the website to do some research himself. 

## Technologies Used

### Languages
This project uses **HTML**, **CSS** and **JavaScript**. 

### Libraries
- [Bootstrap](https://getbootstrap.com/): Its grid, components and classes simplify the website structure and add additional responsiveness. 
- [jQuery](https://jquery.com/): This JavaScript library simplifies DOM manipulation.
- [Favicon.io](https://favicon.io/): Provides favicons to improve website recognition and branding.
- [Font Awesome](https://fontawesome.com/): Provides icons to simplify and visualise content and creates a better UX.
- [Google Fonts](https://fonts.google.com/): Used to style the website font.

### Tools

- [Github](https://github.com/): Hosts the project files and was used to deploy the website to Git Pages. Additionally the Githubs Projects Planner was used to plan the project and keep track of any outstanding tasks (see [here](https://github.com/AnabelaLealCosta19/cosmic-match/projects/1)).
- [Gitpod](https://www.gitpod.io/): Provides a developing environment to write code and commit changes to Github.
- [Git](https://git-scm.com/): Used for version control of the project.
- [Balsamiq](https://balsamiq.com/?gclid=CjwKCAjwh472BRAGEiwAvHVfGsly1Nt9bDZCFUTGCc9I8OfaLtSIcxLhm_WX8911ERsm__luBJslTBoCqgQQAvD_BwE): Used in the surface plane (UXD) to plan my project and create wireframes.
- [Paint 3D](https://www.microsoft.com/en-us/p/paint-3d/9nblggh5fv99?activetab=pivot:overviewtab): Used to crop background image for each device type devices and to remove star constellations names from cards. 
- [Snipping Tool](https://en.wikipedia.org/wiki/Snipping_Tool): Used to make screenshots and to compare different styles side by side.
- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools): Allows styling withing Chrome browser and provides valuable insights when troubleshooting.
- [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln): Changes styling of website to black and pink to show borders and simplify debugging of overflow. 
- [WhatIsMyScreenResolution](http://whatismyscreenresolution.net/): Determines the screen resolution of your current device (this information helps when troubleshooting with developer tools).
- [Nu HTML Checker](https://validator.w3.org/nu/): Validated my HTML code.
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/): Validate my CSS code.
- [Esprima](https://esprima.org/demo/validate.html): Validate my JS code.
- [Diffchecker](https://www.diffchecker.com/): Used to identify mistakes by comparing similar elements of my website (working vs not working).
- [FREEFORMATTER](https://www.freeformatter.com/): Indented my HTML, CSS and JS code.
- [LetterCount](https://www.lettercount.com/): Counted letters of commit messages to ensure they aren't too long.
- [Scribens.com](https://www.scribens.com/): Checked grammar of website and readme content.
- [Am I Responsive](http://ami.responsivedesign.is/): Used to display website across devices for screenshot in product introduction.
- [Tiny PNG](https://tinypng.com/): Compressed images for my project. 
- [Diagram Editor](https://www.diagrameditor.com/): Used to create the diagrams for my readme.
- **Built in screen recorder in Huawei P20 Pro**: Used to record second issue for bug section. 
- [Online Converter](https://www.onlineconverter.com/mp4-to-gif): Used to compress the gif for the bug section. 
- [PowerMapper](https://www.powermapper.com/products/sortsite/checks/browser-compatibility/): Used for browser compatibility tests.
- [Pingdom](https://tools.pingdom.com/): Used to check website speed test.  

## Testing

### Code Validation

- HTML validation: 
    - No errors, [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fanabelalealcosta19.github.io%2Fcosmic-match%2F)

- CSS validation: 
    - Any errors seem to be related to bootstrap's library, my code itself passes
    - [Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fanabelalealcosta19.github.io%2Fcosmic-match%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=de)

- JS validation: 
    - No errors, see details in screenshot below.

 <div align="center">
    <img src="assets/images/readme/js-validator.png" alt="JS validations - results" >
</div>  

### Initial Testing

When initially creating the webiste, I've made sure to test the bootstrap grid before adding any custom styling.

To do so, I have styled the containers, rows and columns with thick borders in different colours. I then tested the grid on different devices in the Developer Tools as well as by changing the width when in "responsive" mode. Like this, I could make sure that the grid behaves as expected and responsiveness is ensured.


### Responsiveness

The responsiveness has been tested throughout the project creation on my desktop, in the Developer Tools (all devices) as well as by changing the width when in "responsive" mode. I furthermore tested my website on my Samsung Galaxy S10 phone and my partner's Huawei P20 Pro without noticing any issues.

### Browsers 

I have tested the responsiveness and functionality of the website on the following browsers: 

- [Google Chrome](https://www.google.com/intl/en_ie/chrome/)
- [Firefox](https://www.mozilla.org/en-US/firefox/new/)
- [Microsoft Edge](https://www.microsoft.com/en-ie/download/internet-explorer.aspx)

The website could not be tested on safari as we don't have any apple devices ourselves. I tried to find a friend that uses apple's devices, but was unable to find someone as I only remembered this shortly before project submission. 

### Functionality testing

Please note that the functionality of the features of this website has been tested throughout the development process. For this I used the website as a player and debugged with help of the Chrome developer tools if it wasn't behaving as expected.  

Unfortunately, I was not able to summarize the functionality testing below as detailed as I'd like to, but I hope that this provides a sufficient overview over the main areas. 

1. First start page modal
    - Default selection under page open is a blank field for name entry and easy difficulty selected.
    - Each of the difficulties highlights and changes when selected without fault.
    - Characters are limited to ten for entering a user name.

2. Repeat Start Page Modal
    - Upon reopening the page there is no name entry field as my name is already listed and the last played difficulty is set to default.
    - Each of the difficulties highlights and changes when selected without fault.
    - Upon clicking "You're not [player name]?" a username entry field appears which is limited to ten characters.
    - This modal only closes when selecting the "Play Now" button.

3. Main Page
    - Player name updated according to my input.
    - Time automatically starts.
    - I cannot flip another card until the first pair has flipped back.
    - Upon pausing the game, time stops and I cannot select another card to be flipped.
    - Resuming continues the countdown and players can continue to flip cards.
    - Flip counter tracks all flip whilst the game is in play, whilst paused no flips can be counted.
    - Matching all cards shows the congratulations modal.
    - Restart button resets time, flip counter, flips any matched cards face down and shuffles cards.

4. Instructions modal
    - Clicking the instructions modal automatically pauses the game whilst opening the modal.
    - Instructions modal will not close unless choosing the "Let`s Find Out" button, when done the timer starts and the game continues.

5. Setting Modal
    - When clicking on the cog icon, the settings modal is opened.
    - In this modal I can change name and difficulty, the modal only closes up choosing the "Confirm Changes" or "Cancel".
    - Selecting "Confirm Changes" changes the settings and name to my choosing and restarts the timer and flip count.
    - Selecting "Cancel" closes the settings modal and resumes gameplay.

6. Congratulations Modal
    - Completing the game will display the congratulations modal which displays my name, asks if I wish to proceed with another round and allows me to choose a difficulty. 
    - This modal only closes when clicking the "Play Again" button.

7. Game Over Modal.
    - Failing to complete the game will display the game over modal which displays my name, asks if I wish to proceed with another round and allows me to choose a difficulty. 
    - This modal only closes when clicking the "Play Again" button.

### Other

- Website Speed Test 
    - Performance grade is overall ok, load time 611ms
    - [Results](https://tools.pingdom.com/#5d080d1c44000000)

- SortSite - Browser Compatibility Tests
    - Minor page issues, overall better than average (see screenshot below)

 <div align="center">
    <img src="assets/images/readme/browser-compability-testing.png" alt="Browser Compatibility Tests - results" >
</div> 

## Existing bugs

1. **First page modal closes even if no player name provided**

<div align="center">
    <img src="assets/images/readme/no-player-name-main-page.png" alt="No player visible in main page" >
</div>

The modal form is being submitted even if nothing has been provided as player name. This is problematic, as no name is displayed in the main page nor in any other modals, where the player's name is being referenced.

Steps taken: 

- Provided minlength="1" attribute to require at least one character for this field. As the field input was required, I expected it to not allow the user to close this modal until some data has been provided. Unfortunately, this did not work for me. 
- I tried to solve it with an if function instead, to ensure that the code for the play now button is only executed when the player field is not empty (please see further details in the screenshot provided). Additionally, I removed the attribute data-dismiss="modal" from the respective button. 

<div align="center">
    <img src="assets/images/readme/no-player-name-provided.png" alt="Code written to try fix this bug" >
</div>


As none of the options above worked and I was under time pressure, I had to stop with the troubleshooting process and proceed writing the readme file. 

2. **When game is paused and settings are changed, the pause icon doesn't reset**

If the player pauses the game first and then changes the settings, the pause icon including functionality is not reset as intended. 

This means, that even though the timer is already running, the resume icon is still displayed upon starting a new game. As a result, the cards cannot be flipped by the user, until he presses the resume button when the event listener for clicking on a card is finally added.  

![Gif: Bug recording](assets/images/readme/bug2-recording.gif)

Steps taken: 

As this issue was discovered shortly before project submission, I was not able to complete a thorough investigation into what could be causing that issue. I added the function resetResumeButton(); to the button "settingsPlayNow" as well as adding the event listener to the card again, but, unfortunately, this didn't have the expected outcome. 

## Deployment

### Deploy project

My project has been deployed to GitHub Pages. To do so, I completed the steps below:

1. Navigated to my repository "cosmic-match"
2. Clicked on **Settings**
3. Under **GitHub Pages**, I used the **Source** drop-down menu and selected "master branch"
4. Clicked on **Save**

Once done, GitHub displayed the following message: "Your site is ready to be published at https://anabelalealcosta19.github.io/cosmic-match/". I clicked on the link and could confirm that the website was successfully deployed. 

### Deployed vs development version

My Github Pages site is built from the master brand. All changes have been saved, committed and pushed. Therefore, there should be no differences between the deployed and the development version.  

### Run code locally

To run code locally, the remote Github repository needs to be cloned. Cloning a repository pulls down a full copy of all the repository data that GitHub has at that point, including every file and folder of the project. Changes can be pushed to the remote Github repository at any time.

Find below the necessary steps to be able to run the code locally. The default instructions relate to Windows, any differences for Mac and Linux have been added in brackets. 

#### Cloning a repository using the command line
1. On GitHub, navigate to the main page of the repository.
1. Under the repository name, click **Clone or download**.
1. **Clone with HTTPS**: Click on the clipboard symbol beside the web URL to clone the repository using HTTPS. To clone using a SSH key (or certificate issued by the SSH certificate authority), click **Use SSH** and then the clipboard symbol.
1. Open Git Bash [*Mac & Linux: Open Terminal*].
1. Change the current working directory to the location you want the cloned directory. 
1. Type **git clone** and paste the URL you copied in step 3.
1. Press enter to create the local clone.

#### Cloning a repository to GitHub Desktop
1. Sign in to GitHub and GitHub Desktop before you start to clone.
1. On GitHub, navigate to the main page of the repository.
1. Under the repository name, click **Clone or download**.
1. **Clone with HTTPS**: Click on **Open in Desktop** to clone the repository and open it in GitHub Desktop.
1. Click **"Choose..."** and navigate to a local path where you want to clone the repository.
1. Click **Clone** to create the local clone.

## Credits

### Media

I exclusively used images as media for my website. 

The images used in this project have been obtained from the following sources:

* **Background image:** Free image downloaded from [pxhere](https://pxhere.com/en/photo/115088). To view the image click [here](https://pxhere.com/en/photo/115088).
* **Card images - front:** Vector images purchased at [Creative market](https://creativemarket.com/). To view the specific product click [here](https://creativemarket.com/skyboxcreative/448990-Constellations-Vector-Set#fullscreen).
* **Card images - back:** Telescope vector obtained from [shutterstock](https://www.shutterstock.com/home). To view the image click [here](https://www.shutterstock.com/image-vector/telescope-flat-icon-on-black-background-599913728).

The image in the project introduction is a screenshot of my own website displayed in Am I Responsive and has, therefore, no typical external source. Additionally further screenshots have been made of this website to visualize certain sections of the readme file.

### Code

Code has been used by me from the following sources: 

Language | Effect | Example | Source | URL
-------- | ------ | ------- | ------ | ---
CSS | Vertically align block-level element with unknown height | style.css, lines 23-27 | [CSS tricks](https://css-tricks.com/) | [here](https://css-tricks.com/centering-css-complete-guide/)
CSS | Styling: glowing text | style.css, lines 46-50 | [Free Frontend](https://freefrontend.com/) | [here](https://freefrontend.com/css-glow-text-effects/)
CSS | Flip cards | style.css, lines 203-221 | [FreeCodeCamp (youtube channel)](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ) | [here](https://www.youtube.com/watch?v=ZniVgo8U7ek&t=298s)
CSS | Combine several conditions in same media query | style.css, lines 446-469 | [MDN web docs](https://developer.mozilla.org/en-US/) | [here](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)
JS | Disable enter key | game.js, lines 72-76 | [Paulund](https://paulund.co.uk/) | [here](https://paulund.co.uk/how-to-disable-enter-key-on-forms)
JS | Shuffle cards | game.js, lines 87-93 | [FreeCodeCamp (youtube channel)](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ) | [here](https://www.youtube.com/watch?v=ZniVgo8U7ek&t=298s)
JS | Define if card if first or second card | game.js, lines 248-266 | [FreeCodeCamp (youtube channel)](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ) | [here](https://www.youtube.com/watch?v=ZniVgo8U7ek&t=298s)
JS | Remove last character from id | game.js, lines 281-283 | [Stackoverflow](https://stackoverflow.com/) | [here](https://stackoverflow.com/questions/1794822/remove-last-character-in-id-attribute)
JS | Check if all elements in array have specific class | game.js, lines 308-315 | [Stackoverflow](https://stackoverflow.com/) | [here](https://stackoverflow.com/questions/31962074/jquery-how-to-check-if-all-element-in-array-have-specific-class)
   
### Acknowledgments

While I  decided to create a memory game, I got the inspiration for the overall theme from my partner Glen Harris. He has always been truly fascinated by astronomy and stars in particular. When looking at the different constellations at night, I had the idea to combine this with my second project. 

## Disclaimer

This website has been created for educational purposes only.