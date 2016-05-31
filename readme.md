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

<a name="unit1"></a>
## Unit 1

<a name="week1"></a>
### Week 1 | Front-end Fundamentals

| [Monday](#w1d1)                    | [Tuesday](#w1d2)                      | [Wednesday](#w1d3)                         | [Thursday](#w1d4)                          | [Friday](#w1d5)                        |
| ---------------------------------- | ------------------------------------- | ------------------------------------------ | ------------------------------------------ | -------------------------------------- |
| KICKOFF!!                          | [Assessment][1-2A] & [Solution][1-2Z] | [Assessment][1-3A] & [Solution][1-3Z]      | [Assessment][1-4A] & [Solution][1-4Z]      | [Assessment][1-5A] & [Solution][1-5Z]  |
| [Install Fest][1-1A]               | [RLab: Command Line][1-1C]            | [RLab: Build a Website][1-2F]              | [RLab: Boostrap Website Replication][1-3F] | [RLab: Functions][1-4E]                |
|                                    | [HTML Basics][1-2B]                   | [Box Model and Positioning][1-3B]          | [Data Types, Variables, Arrays][1-4C]      | [JS Debugging][1-5B]                   |
| LUNCH                              | LUNCH                                 | LUNCH                                      | LUNCH                                      | LUNCH                                  |
| [Navigating the file system][1-1B] | [Chrome Dev Tools][1-2C]              | [ILab: HTML CSS Site Replication][1-3C]    | [Mastering The Flow][1-4D]                 | Fundamental Reviews                    |
| [HLab: Command Line][1-1C]         | [CSS Selector Basics][1-2D]           | [Bootstrap CSS Slides][1-3D]               | [HLab: Functions][1-4E]                    | [Review - Rock, Paper, Scissors][1-5C] |
| -                                  | [CSS Selector Game][1-2E]             | [Bootstrap CSS Lesson][1-3E]               | -                                          | [HLab: JS Koans][1-5D]                 |
| -                                  | [HLab: Simple Website][1-2F]          | [HLab: Boostrap Site Replication][1-3F]    | -                                          | -                                      |

[1-1A]: 00-programming/install-fest/README.md                           "Install Fest"
[1-1B]: 01-workflow/navigating-the-file-system-lesson                   "Navigating the file system"
[1-1C]: https://github.com/wdi-hk-11/lab-command-line                   "HLab: Command line"

[1-2A]: 14-assessments/w01d2.md                                         "Assessment"
[1-2Z]: 14-assessments/w01d2-solution.md                                "Assessment Solution"
[1-2B]: 02-front-end-intro/html-basics-lesson                           "HTML Basics"
[1-2C]: 01-workflow/chrome-dev-tools-lesson                             "Chrome Dev Tools"
[1-2D]: 02-front-end-intro/css-selector-basics                          "CSS Selector Basics"
[1-2E]: http://flukeout.github.io                                       "CSS Selector Game"
[1-2F]: https://github.com/wdi-hk-11/lab-simple-website                 "HLab: Build website"

[1-3A]: 14-assessments/w01d3.md                                         "Assessment"
[1-3Z]: 14-assessments/w01d3-solution.html                              "Assessment Solution"
[1-3B]: 02-front-end-intro/css-box-model-and-positioning                "Box Model and Positioning"
[1-3C]: https://github.com/wdi-hk-11/lab-html-css-site-replication      "ILab: CSS Web Replication"
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

#### Week 1 | Day 1
<a name="w1d1"></a>

- Homework
  - Read [What is Code? (by Bloomberg Business)](http://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/)
  - Read [20 things I've learned about browsers and the web](http://www.20thingsilearned.com/en-US/home)
  - Try the typing exercises on [typing.io](https://www.typing.io/) and see how fast you type code
  - Watch [DNS Explained](https://www.youtube.com/watch?v=72snZctFFtA) to how DNS works

<a name="week2"></a>
### Week 2 | Front-end Fundamentals

| [Monday](#w2d1)                  | [Tuesday](#w2d2)                      | [Wednesday](#w2d3)             | [Thursday](#w2d4)             | [Friday](#w2d5)                 |
| -------------------------------- | ------------------------------------- | ------------------------------ | ----------------------------- | ------------------------------- |
| [JS Objects][2-1A]               | [Assessment][2-2A] & [Solution][1-2Z] | [@Dom Manipulation][2-3A]      | [RLab: Shopping Cart][2-3E]   | [Project Spec][2-5A]            |
| [ILab: JS Objects][2-1B]         | [RLab: Objects & Arrays][2-1E]        | [ILab: Dom Manipulation][2-3B] | [ILab: Tic-Tac-Toe][2-4A]     | [Presentation Guidelines][2-5B] |
| LUNCH                            | [Function and Scope][2-2B]            | LUNCH                          | LUNCH                         | LUNCH                           |
| [JS Arrays][2-1C]                | LUNCH                                 | [JQuery Lesson][2-3C]          | [ILab: 10 Seconds Math][2-4B] | [Agile Framework][2-5C]         |
| [ILab: JS Arrays Problems][2-1D] | [Github Lesson][2-2C]                 | [JQuery Game][2-3D]            | -                             | Project Pitch Day1              |
| [HLab: Objects & Arrays][2-1E]   | [ILab: Github][2-2D]                  | [HLab: Shoppoing Cart][2-3E]   | -                             | -                               |
| -                                | [Read: Git][2-2E]                     | -                              | -                             | -                               |

[2-1A]: 00-programming/js-objects-lesson                                      "JS Objects"
[2-1B]: https://github.com/wdi-hk-11/lab-js-problems-objects                  "ILab: JS Objects"
[2-1C]: 00-programming/js-arrays-lesson                                       "JS Arrays"
[2-1D]: https://github.com/wdi-hk-11/lab-js-problems-arrays                   "ILab: JS Arrays Problems"
[2-1E]: https://github.com/wdi-hk-11/lab-js-problems-objects-and-arrays       "HLab: Objects & Arrays"

[2-2A]: 14-assessments/w02d2.md                                               "Assessment"
[2-2Z]: 14-assessments/w02d2-solution.md                                      "Assessment Solution"
[2-2B]: 00-programming/js-functions-and-scope                                 "Function and Scope"
[2-2C]: 01-workflow/git-github-lesson                                         "Github Lesson"
[2-2D]: https://github.com/wdi-hk-11/lab-git-github                           "ILab: Github"
[2-2E]: https://git-scm.com/doc                                               "Read: Git"

[2-3A]: 02-front-end-intro/js-dom-manipulation-lesson                         "Dom Manipulation"
[2-3B]: https://github.com/wdi-hk-11/lab-js-dom-manipulation                  "ILab: Dom Manipulation"
[2-3C]: 02-front-end-intro/js-jquery-lesson                                   "JQuery Lesson"
[2-3D]: http://jqexercise.droppages.com/                                      "JQuery Game"
[2-3E]: https://github.com/wdi-hk-11/lab-shopping-cart                        "HLab: Shopping Cart"

[2-4A]: https://github.com/wdi-hk-11/lab-js-tic-tac-toe                       "ILab: Tic-Tac-Toe Lab"
[2-4B]: https://github.com/wdi-hk-11/lab-ten-seconds-math                     "ILab: 10 Seconds Math"

[2-5A]: projects/project-01.md                                                "Project Spec"
[2-5B]: projects/presentation_guideline.md                                    "Presentation Guidelines"
[2-5C]: 01-workflow/agile-user-stories-wireframes-lesson                      "Agile Framework"