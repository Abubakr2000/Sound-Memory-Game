# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Abubakr Alijanov**

Time spent: **6** hours spent in total

Link to project: (https://glitch.com/edit/#!/handsome-jasper-pantry?path=style.css%3A1%3A0)

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

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Pattern is randomly generated
- [x] Whole background has been changed from regular color to a cool image 

## Video Walkthrough (GIF)

For winning case:

![](https://github.com/Abubakr2000/Sound-Memory-Game/blob/main/walkthrough1.gif)

For losing case:

![](https://github.com/Abubakr2000/Sound-Memory-Game/blob/main/walkthrough2.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
![https://www.w3schools.com/css/css_font.asp]
![https://www.w3schools.com/css/css_colors.asp]
![Google photos]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

Overall, the process was not hard. Initially, it seems somehow confusing to set up a project, and get started in GLITCH IDE. With help of given instructions and browsing Glitch IDE, I overcame my confusion and got familiar with this software. Although completing project with required functionalities was not so hard, adding optional features was somehow challanging. Initially, i could not figure out how to change the regular color game button to an image when clicked. Especially, as uploaded image pixels were different, image didn't show properly in game button. Then, I matched pixles of uploaded image with game button height & width pixels to 250px & 250px. Finally, after that, images showed properly. Moreover, while adding a functionality, which is only losing after 3 mistakes, I did not realize that i did not call "playsequence" function if mistakes did not reach to 3. This was causing a program not to playback the pattern if a gamer makes a mistake. Then, I could find my mistake while doing debugging.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[YOUR ANSWER HERE]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.kapwing.com/videos/6247ec79acf9c8006d59f6ec)


## License

    Copyright [Abubakr Alijanov]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
