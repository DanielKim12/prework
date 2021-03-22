# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Guk il Kim

Time spent: 4.5 hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [y] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [y] "Start" button toggles between "Start" and "Stop" when clicked. 
* [y] Game buttons each light up and play a sound when clicked. 
* [y] Computer plays back sequence of clues including sound and visual cue for each button
* [y] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [y] User wins the game after guessing a complete pattern
* [y] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [n] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [n] Buttons use a pitch (frequency) other than the ones in the tutorial
* [y] More than 4 functional game buttons
* [n] Playback speeds up on each turn
* [n] Computer picks a different pattern each time the game is played
* [n] Player only loses after 3 mistakes (instead of on the first mistake)
* [n] Game button appearance change goes beyond color (e.g. add an image)
* [n] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [n] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
//I have not used any other sources but the page instructions itself. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
//the challenges that I encountered while creating this submission was that class id in html format, since I am not fully experienced with 
class id format for the id implementation, I had to go back and learn what it does and how it works. Additionally, in script.js when I was 
trying to implement the logic of the guess function in the game looking at the flow chart, I had some difficulties coming up with the conditional 
statement to fit the flow chart requirements in order to function the game itself. I skimmed at the ans of the guess function and got the idea of how 
to implement my conditional statement. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
//Through this assignment, I learned more about conditional statements in JS and more features on CSS. Though, I did had some questions after the assignements that are
why is it necessary to put the '#' infront of button items in CSS implementation and also why can't we combine the .lit and active status together under the button(1,2,3,4) 
implementation of the CSS? Additionally, for the tone part, I was able to catch up on the implementation but wasn't able to recall all the steps that was being 
implemented under the functions. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
// If I had more hours to work on this project, I would spent more time working on challenge/optional implementations. First, I would work on Math.random() to generate
random numbers instead of having set patterns. I wasn't so sure of how to use its syntax and to implement it under the startGame(), I wasn't able to generate one. Second, I will 
work on the time-efficeincy that after every guesses the game will speed up and give the user limited time to enter the guess. This feature is not that challenging to come up one 
but will require multiple implemenatations of if-else conditions and will also have to deal with for loop that tracks the status of the game. Lastly, I will work on the 
three warning system that the users dont lose the game right away after the first guess but gets 2 warning and lose the game on the third error. This will require one counting varibale 
that to track the numbers of errors that the user made and everytime the losegame() pops up instead of terminating the game I will have to replace it with the incremnenting the countinbg 
varibales, and set a condition/function that checks if the error is at 2nd warning pop the message to alert the player and once it hits 3 then it will terminate the game with the error message "You lost". 
These implementations were a bit time-consuming since we need to generate flow chart and know how to approach the implementation, that I wasn't able to complete it, however, if I get extra time 
with this assignment I would try to complete these features as well.



## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.