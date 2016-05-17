![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)
# GA | Web Development Immersive

| Unit                 | Topic                              | Topic                              | Project
|------------          |------------------------------------|------------------------------------|--------------------------------------
| **[UNIT 1](#unit1)** | [1. Front-end Intro](#week1)       | [2. Dynamic Frontend](#week2)      | [3. Project 1: Build a game](#week3)
| **[UNIT 2](#unit2)** | [4. AJAX & MongoDB](#week4)        | [5. MongoDB & Hapi.js](#week5)     | [6. Project 2: Web API App](#week6)
| **[UNIT 3](#unit3)** | [7. Ruby and SQL DB](#week7)       | [8. Ruby on Rails](#week8)         | [9. Project 3: Rails App](#week9)
| **[UNIT 4](#unit4)** | [10. MVC with Angular](#week10)    | [11. Final Project](#week11)       | [12. Final Project](#week12)

# Short Hands
- ILab = Inclass Lab (Doing and reviewing the lab inclass on the same day)
- HLab = Homework Lab (Doing the lab partly inclass and the rest for homework)
- RLab = Reviewing Lab (Review the lab that was assigned for homework the previous day)

# Symbols
- + = Need to create or edit
- * = create new repo for practice code
- x = relink lesson

# Subject Code
00-programing

<a name="unit1"></a>
## Unit 1

<a name="week1"></a>
### Week 1 | Front-end Fundamentals

| [Monday](#w1d1)                    | [Tuesday](#w1d2)                      | [Wednesday](#w1d3)                         | [Thursday](#w1d4)                          | [Friday](#w1d5)                        |
| ---------------------------------- | ------------------------------------- | ------------------------------------------ | ------------------------------------------ | -------------------------------------- |
| KICKOFF!!                          | [Assessment][1-2A] & [Solution][1-2Z] | [Assessment][1-3A] & [Solution][1-3Z]      | [Assessment][1-4A] & [Solution][1-4Z]      | [Assessment][1-5A] & [Solution][1-5Z]  |
| [Install Fest][1-1A]               | [RLab: Command Line][1-1C]            | [RLab: Build a Website][1-2F]              | [RLab: Boostrap Website Replication][1-3F] | [RLab: Functions][1-4E]                |
|                                    | [HTML Basics][1-2B]                   | [Box Model and Positioning][1-3B]          | [*xData Types, Variables, Arrays][1-4C]    | [*xJS Debugging][1-5B]                 |
| LUNCH                              | LUNCH                                 | LUNCH                                      | LUNCH                                      | LUNCH                                  |
| [Navigating the file system][1-1B] | [Chrome Dev Tools][1-2C]              | [+ILab: CSS Website Replication][1-3C]     | [Mastering The Flow][1-4D]                 | Fundamental Reviews                    |
| [HLab: Command Line][1-1C]         | [CSS Selector Basics][1-2D]           | [Bootstrap CSS Slides][1-3D]               | [HLab: Functions][1-4E]                    | [Review - Rock, Paper, Scissors][1-5C] |
| -                                  | [CSS Selector Game][1-2E]             | [Bootstrap CSS Lesson][1-3E]               | -                                          | [HLab: JS Koans][1-5D]                 |
| -                                  | [+HLab: Build a Website][1-2F]        | [+HLab: Boostrap Website Replication][1-3F]| -                                          | -                                      |

[1-1A]: 00-programming/install-fest/README.md                           "Install Fest"
[1-1B]: 01-workflow/navigating-the-file-system-lesson                   "Navigating the file system"
[1-1C]: https://github.com/wdi-hk-11/lab-command-line                   "HLab: Command line"

[1-2A]: 14-assessments/w01d2.md                                         "Assessment"
[1-2Z]: 14-assessments/w01d2-solution.md                                "Assessment Solution"
[1-2B]: 02-front-end-intro/html-basics-lesson                           "HTML Basics"
[1-2C]: 01-workflow/chrome-dev-tools-lesson                             "Chrome Dev Tools"
[1-2D]: 02-front-end-intro/css-selector-basics                          "CSS Selector Basics"
[1-2E]: http://flukeout.github.io                                       "CSS Selector Game"
[1-2F]: https://github.com/wdi-hk-11/lab-html-css-website               "HLab: Build a website Lab"

[1-3A]: 14-assessments/w01d3.md                                         "Assessment"
[1-3Z]: 14-assessments/w01d3-solution.html                              "Assessment Solution"
[1-3B]: 02-front-end-intro/css-box-model-and-positioning                "Box Model and Positioning"
[1-3C]: https://github.com/wdi-hk-11/lab-css-site-replication           "ILab: CSS Web Replication"
[1-3D]: 02-front-end-intro/css-bootstrap-lesson                         "Bootstrap CSS Lesson"
[1-3E]: https://presentations.generalassemb.ly/649ce6766e83f246e122     "Bootstrap CSS Slides"
[1-3F]: https://github.com/wdi-hk-11/lab-bootstrap-site-replication     "HLab: Bootstrap Web Replication"

[1-4A]: 14-assessments/w01d4.md                                         "Assessment"
[1-4Z]: 14-assessments/w01d4-solution.md                                "Assessment Solution"
[1-4C]: 00-programming/js-data-types-variables-and-arrays               "Data Types, Variables, Arrays"
[1-4D]: 00-programming/js-mastering-the-flow-lesson                     "Mastering The Flow"
[1-4E]: https://github.com/wdi-hk-11/lab-js-functions                   "HLabs: Functions"

[1-5A]: 14-assessments/w01d5.md                                         "Assessment"
[1-5Z]: 14-assessments/w01d5-solution.md                                "Assessment Solution"
[1-5B]: 00-programming/js-debugging-lesson                              "JS Debugging"
[1-5C]: 00-programming/js-fundamental-reviews/rock-paper-scissors.js    "Review - Rock, Paper, Scissors"
[1-5D]: https://github.com/wdi-hk-11/JavaScript-Koans                   "HLab: JS Koans"

<a name="week2"></a>
### Week 2 | Front-end Fundamentals

| [Monday](#w2d1)                  | [Tuesday](#w2d2)             | [Wednesday](#w2d3)             | [Thursday](#w2d4)             | [Friday](#w2d5)                 |
| -------------------------------- | ---------------------------- | ------------------------------ | ----------------------------- | ------------------------------- |
| [JS Objects][]                   | [RLab: Array Problems][2-2C] | [Dom Manipulation][2-3A]       | [RLab: Shopping Cart][2-5A]   | [Project Spec][2-5B]            |
| [+ILab: JS Objects][]            | [Function and Scope][2-2A]   | [RLab: Dom Manipulation][2-3B] | [ILab: Tic-Tac-Toe][2-5D]     | [Presentation Guidelines][2-5C] |
| LUNCH                            | LUNCH                        | LUNCH                          | LUNCH                         | LUNCH                           |
| [JS Arrays Lesson][2-2B]         | [Github Lesson][2-1B]        | [JQuery Lesson][2-4A]          | [ILab: 10 Seconds Math][2-5E] | [Agile Framework][2-1A]         |
| [ILab: JS Arrays Problems][2-2C] | [ILab: Github][2-1C]         | [JQuery Game][2-4B]            | -                             | Project Pitch Day1              |
| [+HLab: Objects & Arrays][]      | [Read: Git][]                | [HLab: Shoppoing Cart][2-4C]   | -                             | -                               |
| -                                | -                            | -                              | -                             | -                               |

<a name="week3"></a>
### Week 3 | Project 1

| [Monday](#w3d1)                          | [Tuesday](#w3d2)                        | [Wednesday](#w3d3)                      | [Thursday](#w3d4)                       | [Friday](#w3d5)                         |
| ---------------------------------------- | --------------------------------------- | --------------------------------------- | --------------------------------------- | --------------------------------------- |
| Project Pitch Day2                       | Daily Standup                           | Daily Standup                           | Daily Standup                           | Daily Standup                           |
| WireFrame + Trello + Coding Begins       | -                                       | -                                       | -                                       | -                                       |
| LUNCH                                    | LUNCH                                   | LUNCH                                   | LUNCH                                   | LUNCH                                   |
| -                                        | -                                       | -                                       | -                                       | *JS CHANGE FREEZE*                      |
| -                                        | -                                       | -                                       | -                                       | Final touch up (HTML & CSS)             |
| -                                        | -                                       | -                                       | -                                       | Presentation                            |