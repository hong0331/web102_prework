# WEB102 Prework - FundmeGame

Submitted by: EunyoungHong (Zoey)

FundmeGame is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 5 hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [x] Search Bar has added. It is case-insensitive for the users to find the specific game.

The following **optional** features can be improved:
- Add the fund button for the unfunded game 
- Create the database and when new data is added, update the page itself for the funding status.

## Video Walkthrough

Here's a walkthrough of implemented features:



https://user-images.githubusercontent.com/67743970/216782254-9d8250b9-0376-4789-8f8a-644fbbc79cbd.mov




## Notes

Describe any challenges encountered while building the app. 
- While creating the search bar, I was struggling to filter and display the game according to the user input.

   I first tried for the filtering method to be ` let FoundList = GAMES_JSON.filter( game =>
        game.name.toLowerCase() == value.toLowerCase()
    );` , which did not work. 
    After searching up the solutions, I improvisioned the error with `contains` method.

## License

    Copyright [2023] [EunyoungHong]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
