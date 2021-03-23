# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Samantha Zhang**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/codepath-prework-sazhang

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)

The following **additional** features are implemented:

* N/A

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![http://g.recordit.co/ePW7vWgJER.gif](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[Referenced JavaScript array syntax: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[One challenge I faced in this submission was implementing optional feature 4. 
After making a global variable for the number of mistakes, I added an incrementer for the else statement covering if the guess was incorrect. 
I realized that I would also need an if statement to ensure the loseGame() function wouldn’t be called until the user reached their third mistake. 
Thinking I was done, I decided to test the game. After making a mistake in the pattern, I noticed the clue sequence didn’t play again. 
If the user guessed it incorrectly in the first place, chances are they didn’t remember the sequence and wouldn’t be able to get it on their second or third attempt. 
After some brainstorming and play testing, I decided it was necessary to replay the sequence and added a call to playClueSequence() if the game was not over.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[Is it possible to deploy the gitch code and make a website from it? If not, what kind of steps would need to be done in order to make the memory game launchable? 
How would the code for this project be done locally (i.e. not using an IDE like glitch)? Is it possible to host multiple users on the website (ex: multiplayer games) and, if so, how?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had more time to work on this project I would like to implement optional features 5 and 6. 
Also, I would find a way to make it so that the users can’t press buttons while the clue sequence is playing. 
I don’t have much experience with CSS, but I think the code would be cleaner if I could abstract the button functions (in order to remove all the repetitive code).
I would also find a way to display to the user their mistake counter since they might lose track of how many mistakes they have made so far. 
I think it would add to the user experience if I could give users the ability to input how long they want the pattern to be.
A feature that would be cool to implement is having different preset sound options. For example, there could be buttons representing music genres. 
If the user pressed the pop song button, completing the pattern would produce the tune of a random pop song.]



## License

    Copyright [Samantha Zhang]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.