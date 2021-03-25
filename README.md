# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Ivy Tong

Time spent: 3 hours spent in total

Link to project: https://raspy-furtive-fur.glitch.me


## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:![]


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
![]![](https://i.imgur.com/zrxhPIp.gif)



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A challenge I encountered was understanding what each line of code did in the playTone, startTone, and stopTone functions in the script.js file. I overcame this problem by looking at the differences between the three functions. I observed what code was similar and what code was different. I then thought about the different behaviors of each of these functions and how the similarities and differences in the code reflected these similarities and differences in behavior of the functions. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I would like to learn more about how we can connect different databases. I have previously worked on a project that involved multiple databases. However, the project didn’t involve connecting the different databases, so I would love to learn more about how we can retrieve information from one database and use it in another database. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
Thinking about user experience, I think the game would be a lot more fun if you could have the opportunity to compete with other people. I would work on implementing a feature that would allow you to play with another user. The idea I have would involve both of the users to take turns playing on the same device. One player would repeat the pattern back first and then it would be the other player's turn to do the same. The players would alternate going first each round. For example, if player one went first this round, then player two would go first in the next round. There would  be a scoring system to keep track of both the player's scores and by the end of the game, whichever player has the higher score would win the game. The game wouldn't end automatically if one player repeated the pattern wrong like it currently does. 




## License

    Copyright Ivy Tong

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.