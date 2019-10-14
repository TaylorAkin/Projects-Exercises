# Widget Simulator (Final Portfolio)

### Description

Create a webpage that simulates a mobile or desktop layout with apps and widgets

For this project we will be using react to componentize all our vanilla javascript projects, and laravel to add all of our react components to a home screen where users can decide what to click on.

### Table of contents

<!--ts-->

- [Project/Exercise Name](<#Phone-Simulator-(Final-Portfolio)>)
- [Description](#Description)
- [Table of Contents](#table-of-contents)
- [MVP (Minimum Viable Product)](#MVP)
  - [Wireframe](#Wireframe)
  - [Tech Stack](#Tech-Stack)
- [Process](#process)
  - [Setup](#Setup)
  - [Develop](#Develop)
  - [Deploy](#Deploy)
- [Requirements](#Requirements)
  - [Additional Requirements](#Additional-Requirements)
  - [Stretch Goals](#Stretch-Goals)
- [Additional Resources](#Additional-Resources)
  <!--te-->

### MVP

By default, the app should show off your projects in a clean and concise format, and be able to be re-arranged in the code to create different layouts

#### Wireframe

Option 1
![wireframe](../wireframes/mobile-widgets.png)
Option 2
![wireframe](../wireframes/desktop-widgets.png)

#### Tech Stack

1. HTML
2. CSS
3. JS
4. React.JS
5. MySQL
6. PHP
7. Laravel

### Process

##### Setup:

1. [Create GitHub repo (either online or locally)](../git-instructions.md), for example: `my-app`
2. Create necessary files for application and view in VS Code
   - Run shell script to expedite process unless you are using a framework
   - _If you are using a framework, disregard the "Application File Structure" section_
3. Import and route necessary css/js files (E.g. Bootstrap)
4. Save all and create your first commit to `master`, **then** switch to a dev branch

##### Develop:

1. Create a `dev` branch to commit your code to
2. Add content and elements to your website
3. View changes and test locally
4. Save often, and commit to your development branch on GitHub when important changes happen
5. Push your commits to GitHub remote
6. For bug fixes, refactored code, and feature branches, you must create a branch off of `dev` onto a `new-feature` branch and create a PR into dev when complete

##### Deploy:

1. Create a Pull Request from `dev` into `master` on GitHub
2. Confirm code is up to date and works correctly
3. Push Final Portfolio to Google Cloud remote
4. Post links to your GitHub repo and the Google Cloud Link to the Projects Slack channel

---

### Requirements

To complete the assignment, you must complete the following:

1. Keep the original projects in their repos, you can use them as reference, but since you will be creating all of these in react.js, you will not need to copy old code over, but rather create a new version from scratch that lives in this repo instead.
2. Component-ize each of the following vanilla JS project with the following additional requirements:
   - Clock and Countdown Timer will be one component with a prop that says which view to display, and a prop that is the start button for the countdown timer
   - Weather app shows a minified icon version of the weather on the main screen, and when you click on the app, it should show the full weather app
   - CRUD Component Clone lets you perform an action without specifically clicking on the app to load it (iOS long press)
   - Calculator, and To-Do List retains state and data in case someone exits app and re opens it (prop to force quit)
   - Mind Reader, sliding puzzle and Tic-Tac-Toe acts as a combined game center app that lets the user select which game to play (also maintains state so a player can come back and pick up where they left off)
3. The following apps do not need to be added into the componentized version, but instead, a dedicated section with descriptions of each that links to their respective GitHub repos should exist, as they are standalone WebApps/Sites:
   - Blog
   - Campaign Website
   - PHP 1
   - PHP 2
4. Use the entire tech stack to complete the project
5. Website must be responsive
6. Push to Google Cloud
7. Link Google Cloud live link to your github repo in README.md and the [project description](https://stackoverflow.com/questions/7757751/how-do-you-change-a-repository-description-on-github)

#### Additional Requirements

- Style your app as you wish
- Use the tools and technologies covered in class to complete your website. To see what we have covered, check the [Class Resources Repo](https://github.com/bootcamp-students/Resources).
- Your repo should be public so that others can see your code and comment on it.
  - _**Remember to push to GitHub!**_
  - Potential employers will view your GitHub profile, so activity is crucial!

#### Stretch Goals

- Create a detailed MVP
- Have an in-app toggle for mobile/desktop view

#### If you finish early...

1. Continue to add your own content, additions, and pages to your site and improve the styling.
2. Add info to your projects README.md [README.md Best Practices](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
3. Add links and resources from this week to the [Class Resources Repo](https://github.com/bootcamp-students/Resources) by forking the repo and then initiating a pull request with your additions to the .md file.

### Additional Resources

- Ask questions :-)
- [Class Resources Repo](https://github.com/bootcamp-students/Resources)
- Learn more about [Good GitHub Practices](https://guides.github.com)

For more information about portfolios, see these articles:

- [Google](https://www.google.com/search?q=developer+portfolio&oq=developer+portfolio&aqs=chrome..69i57j0l5.3263j1j7&sourceid=chrome&ie=UTF-8)
- [GitHub article](https://techbeacon.com/app-dev-testing/what-do-job-seeking-developers-need-their-github)
- [LinkedIn](https://medium.com/@samanthaming/tips-to-optimize-your-linkedin-profile-for-developers-77777c1e2c2e)
