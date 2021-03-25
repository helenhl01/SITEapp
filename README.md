# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Helen Liu**

Time spent: **3** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![memorygame](https://user-images.githubusercontent.com/73402353/112419538-9802d580-8cf9-11eb-98f1-db874db3afaf.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

   https://developers.google.com/web/updates/2017/09/autoplay-policy-changes#webaudio

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
  
  I didn't have a lot of experience with building webpages before this prework challenge, outside of a hackathon group effort (though I did learn a lot through that). One big challenge I faced with this prework was getting the audio to work-I've never implemented audio in a language other than Python, so figuring it out in Javascript gave me so trouble. Although the audio worked perfectly at first, I soon realized that it had stopped playing and the console kept showing an error about the AudioContext function. Upon a little digging around, I realized that this was a problem with the Google Chrome browser, and I would need to implement additional functions were to fix it. Instead, I opted to use Firefox to complete the code, which eliminated the problem without any extraneous code that may not work on other browsers. I also faced a bit of dilemma when deciding between functionality and design tradeoffs, which I know is often an important decision, like choosing a pre-established musical sequence or coding a function to choose random notes each time, and though I could have done the latter, I opted for the former. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
 
 Web development has always been very interesting to me because of its ubiquity and how it makes use of three different programming languages, all playing a different role but interacting together to form a website. Today, websites are some of the most important tools for communicating with people and spreading messages, so I'd love to learn more about web development. I'm still not completely fluent on how the three languages interact and knowing all the three pieces to get something as simple as a button to work without lots of referring to help, so that's something I'd like to learn more about. I'm also very interested in working with databases, since they can be such a powerful and critical part of a website. I'd also like to learn more about polishing user interfaces beyond the simple buttons and drop-down menus that I have used in the past.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
 
 If I had more time on this project, I would have focused on changing the actual appearance of the game, as well as a couple functionalities to make it more competitive. With the appearance, I would have polished the design of the buttons and the website in general, probably adding different colors and effects to the button presses (like a clicking sound to the start/stop button, for example). To improve the game play, I would add a countdown timer in the corner, showing the player how much time they had left. I'd also make the notes randomly selected, rather than a limited array, so the game could go on for as long as the player remembered the sequence. To go along with that, I would add a score counter to keep track of how long they had been playing for. This score counter could not only keep track of the number of correct notes they had played, but also give bonus points for speed. 

## License

    Copyright Helen Liu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
