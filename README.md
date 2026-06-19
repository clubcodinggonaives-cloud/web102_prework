# WEB102 Prework - Sea Monster Crowdfunding

Submitted by: **Desulma Jhonsley**

**Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **4** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented features:

[![Video Walkthrough](https://www.loom.com/share/132caf7048a847aabd8eb167065ec36a)](https://www.loom.com/share/132caf7048a847aabd8eb167065ec36a)

The walkthrough demonstrates the fully functional Sea Monster Crowdfunding page, including:
- The **Stats section** displaying total individual contributions (19,187), total dollars raised ($800,268), total number of games (11), and the top two most funded games (Zoo Tycoon: The Board Game 🥇 and How to Read Minds 2 Kit 🥈)
- The **Introduction section** with the dynamically generated description showing how much has been raised and how many games remain unfunded
- The **Our Games section** showing all 11 game cards with images, names, descriptions, and backer counts
- The **filter buttons** in action — switching between all games, funded-only games (4), and unfunded-only games (7)

Video created with [Loom](https://www.loom.com)

## Notes

The trickiest parts were chaining `reduce` correctly to accumulate backer and pledge totals across all games, and using the ternary operator inside a template literal to keep the description grammatically correct ("game remains" vs "games remain") based on the count of unfunded games.

## License

    Copyright 2025 David

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
