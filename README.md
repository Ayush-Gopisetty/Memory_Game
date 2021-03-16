# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ayush Gopisetty**

Time spent: **7** hours spent in total

Link to project: https://glitch.com/edit/#!/fate-bald-mousepad

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](http://g.recordit.co/2zEHozGS20.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
The outside resources I used to help me complete my submission are https://www.w3schools.com/ and https://www.the-art-of-web.com/javascript/creating-sounds/.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The challenge in creating this submission is that after trying to play the first sequence of clues, it is difficult for me to try to make the following pattern of clues play out to the user. To overcome this challenge, I first had to figure out which part of my code was causing this challenge to occur. After finding out which part of my code was making this challenge, I realized that the guess function in my script.js file was causing this challenge. I realized that I forgot to add an else statement that makes the player progress to the following clue sequence after the if statement, which checks that the user is at the last turn. To overcome the challenge, I had to add the else statement, which allows the user to progress to the following clue sequence, after the if statement, which checks that the user is at the last turn. Also, I realized that I forgot to add an else statement, which lets the user know that the user lost the game and ends the game, after the if statement, which checks that the user had guessed the sequence correctly. After adding these else statements, I overcame the challenge, and I made the following pattern of clues play out to the user. That is a challenge I encountered when creating this submission and how I overcame the challenge.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
The questions about web development that I have after completing my submission are how to make the elements of the web page display correctly when resizing the web page, how to properly check if the buttons on your webpage work properly as intended, and what are the ways I can make a website look more professional? I have other questions about web development. These questions include how to make the website display correctly on any device, how to make the website more user-friendly and interactive, and what are the ways in which users can easily browse the website? These are the questions about web development that I have after completing my submission.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on this project, I would spend a few more hours adding additional features like adding a feature where you would have three guesses for guessing each pattern instead of having one guess. Also, if the user incorrectly attempts a sequence three times, the game would immediately be over. I would also display the number the guesses the user made and the number of guesses the user would have remaining to help the user out in the game. Another feature that I would add to the project if I had a few more hours is that I would add a timer to the project, and I would make the user have fifteen seconds to attempt a pattern. If the user doesn't guess the sequence within fifteen seconds, the user will lose a remaining guess. Also, I will display a timer for the user to know how much time the user has to guess the pattern. The timer is shown to the user after the user sees the sequence. The timer will reset to fifteen seconds after each series until the user has won the game or lost the game. Also, when the user stops the game, the timer will stop displaying to the user. When the user starts the game, the timer will show fifteen seconds, and the timer will begin after the user sees the sequence. That is what I would do if I had a few more hours to work on the project.



## License

    Copyright Ayush Gopisetty

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
