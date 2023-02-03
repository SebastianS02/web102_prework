# WEB102 Prework - *Sea Monster*

Submitted by: **Sebastian Stec**

**Sea Monster** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **7** hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [X] Improved coloring of the website by adding sea-themed colors through CSS.
* [X] Improved user experience with buttons by adding a shadow and changing the cursor to a pointer when hovering over each button.

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://user-images.githubusercontent.com/96634770/216686629-f76cf579-f47f-48ff-9265-a9299fd213c8.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

![ezgif com-gif-maker](https://user-images.githubusercontent.com/96634770/216686629-f76cf579-f47f-48ff-9265-a9299fd213c8.gif)


GIF created with QuickTime Player and ezgif on MacOS

## Notes

One of the biggest challenges I faced was understanding the reduce function and how the accumulator variable worked with it. I was also familiarizing myself with arrow functions while trying to learn the reduce function, so learning how to set up the two parameters along with how to use them took me a long time to finally grasp.

Another challenge I faced was getting the buttons to work. While the filter functions were easy to write, connecting the buttons with the DOM elements and adding event listeners was something I haven't done before, so that was a challenge. I also ran into one very small error that took me almost an entire day to fix, and that was with adding the event listeners to those buttons. I was not aware that when calling functions in JavaScript, you should not include the parentheses at the end of the function name. Calling a function properly would be something like 'filterUnfundedOnly', not 'filterUnfundedOnly()'.

My last major challenge was figuring out template literals, as I have never used them prior to this pre-work. 

## License

    Copyright [2023] [Sebastian Stec]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
