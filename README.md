## Milestone Project Three | Project Pal

![Website overview]

[Live website can be viewed here](https://flask-tsk-manager.herokuapp.com/)

## About 
This website has been created for my Milestone 3 Datacentric Development project.I took inspiration from Codes Institute Task Manager Mini Project. As I struggled with learning python I decided I would take the concept and develop a project planner called 'Project Pal' that is sepcifically created to help manage tasks with Code Institutes Milestone Projects and Hackathons. 

## Table of Contents
* [User Expierence](#User-Expierence)
    * [Site owner goals](#site-owner-goals)
    * [User Stories](#User-Stories)
    * [First Time Visitor Goals](#First-Time-Visitor-Goals)
    * [First Time Visitor Goals for Admins](#First-Time-Visitor-Goals-for-Admins)
    * [Returning Visitor Goals](#Returning-Visitor-Goals)
* [Design](#Design)
    * [Colors](#Colors)
    * [Wireframes](#Wireframes)
    * [Typography](#Typography)
* [Features](#Features)
* [Future Features](#Future-Features)
* [Technologies](#Technologies)
    * [Languages](#Languages)
    * [Frameworks & Tools](#Frameworks-&-Tools)
* [Deployment](#Deployment)
* [Credits](#Credits)
* [Acknowledgements](#Acknowledgements)

## User Expierence

### Site Owner Goals:
* As a site owner I want to create an attractive, responsive, easy to use task manager
* As a site owner I want to create an application to work as intended, Create, Read, Update & Delete
* As a site owner I want to create an application that is easy to navigate 
* As a site owner I was to create a site with different functionality for users and admins

### User Stories:

**First Time Visitor Goals for Users**
* As a first time visitor, I want to be able to register and login easily.
* As a first time visitor, I want the application to be attractive and easy to read.
* As a first time visitor, I want the application to be responsive to whichever device I am using it on.
* As a first time visitor, I want to be able to navigate around the different pages of the application easily.
* As a first time visitor, I want to be able to clearly see my tasks that I have to do .
* As a first time visitor, I want to be given a choice of categories to add tasks to

**First Time Visitor Goals for Admins**
* As a first time visitor, I want the application to be attractive and easy to read.
* As a first time visitor, I want the application to be responsive to whichever device I am using it on.
* As a first time visitor, I want to be able to navigate around the different pages of the application easily.
* As a first time visitor, I want to be able to manage categories for the task manager.
* As a first time visitor, I want to be able to clearly see my tasks that I have to do .
* As a first time visitor, I want to be given a choice of categories to add tasks to

**Returning Visitor Goals:**
As a returning user, I want to be able to see my tasks cleary 
As a returning user, I want to be able delete completed tasks
As a returning user, I want to be able to see add tasks cleary 
As a returning user, I want to login easily
As a returning user, I want to navigate around the application easily 

### Design:
* The design of the website was chosen with the application in mind. It was designed to be visually pleasing for users with an easy UX. The colors were chosen with two established brands in mind, ‘Code Institute’ and ‘Hubspot’. Since the project was created to manage Milestone projects and Hupspot has a great ‘Task Manager’ the inspiration was taken from these brands which have a similar color palette. 

### Colors

* I created a color scheme of deep-orange and navy which were from the brand colors that I mentioned in the ‘Design section’. Deep-orange and navy are bold string colors and compliment the blockchain theme. Blue is the branded color for the

### Wireframes

* Balsamiq was used to create the wireframes for desktop, mobile and tablet.

* The finished website is the same as the original wireframes.

* The links to each one can be found here:
  * Desktop
  * Mobile
  * Tablet

### Typography

* I chose 'Poppins' from Google Fonts. I chose this font because:

* Each letterform is nearly monolinear, with optical corrections applied to stroke joints where necessary to maintain an even typographic color, which I thought was fitting. It's also a sans-serif font which is more accessible for people with dyslexia. Sans-serif is the back-up font if poppins fails.

### Features

**Register page**
  * Nav bar
    * With restricted views for non registered users 
  * A motivating productivity quote
    * To provide motivation
  * Register form
    * With required fields to ensure correct and validate registration
  * Redirect users to login page 
    * Feature added to ensure clear and easy navigation around the site

**Login page**
 * Nav bar
    * With restricted views until users are logged in
 * A motivating productivity quote
    * To provide motivation
 * Register form
    * With required fields to ensure correct and validate registration
 * Redirect users to register page 
    * Feature added to ensure clear and easy navigation around the site

**Home Page**
 * A Navbar
    * To navigate through the application
 * A search bar
    * To easily search for tasks
 * A motivating productivity quote
    * To provide motivation
 * Task list with python automation 
    * Automatically updates with tasks are added or completed

**Profile page**
 * A Navbar
    * To navigate through the application
 * Display option for ‘User Name’
   * To personalize the experience
 * Add Task Btn
   * Replicated the Btn here for convenience 
 * A motivating productivity quote
   * To provide motivation

**New task**
 * A Navbar
   * To navigate through the application
 * A motivating productivity quote
   * To provide motivation
 * Card panel with prompts to add tasks and task information
   * Includes materialize ‘Due date picker’ and ‘Urgent’ switch
 * Add task btn 
   * Btn updates the task on the ‘Home’ task list

**Manage Categories**
 * A motivating productivity quote
    * To provide motivation
 * Add task btn 
    * Btn updates the category on the manage category pages and in the ‘choose category’ option when adding a task with ‘edit’ and ‘delete’ btns

**Log out page**
 * Flash message
    * You have been logged out
 * Login form 
    * For users to log back in 
 * Redirect users to register page 
    * Feature added to ensure clear and easy navigation around the site

### Future Features
 * Include an API that will automate and update positive quotes on each page of the application 
 * Include the option to add sub-tasks per task with the option to tick off subtask as they are completed 
 * Include an ‘About’ page with a mission statement and a section on productivity and motivation to work better
 * Allow user to add a profile image to their account.
 * Allow the user to edit their username or password
 * Allow more than one Admin by not just using the Admin username.
 * Using emailJS give the user the option to signup to a news letter and recieve emails relevant to the site.
 * Allow any user to add a further review to any review already added on the site. 
 * Increase the applications accessability score

### Technologies used

* Languages used
  * [HTML5](https://en.wikipedia.org/wiki/HTML5)
  * [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)
  * [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
  * [Python](https://en.wikipedia.org/wiki/Python_(programming_language)

### Frameworks, Libraries and Programs Used

* [Materialize](https://materializecss.com/) 
   * Materialize was used to help build the structure of the website and add responsiveness across different screen sizes. It also supplied some styling and built in components such as the modal.
* [Balsamiq](https://balsamiq.com/)
   * I used balsamiq to design and draw up my wireframes before starting the project.
* [Font Awesome](https://fontawesome.com/)
   * Font awesome was used to add all icons used on the site.
* [Gitpod](https://www.gitpod.io/)
   * Gitpod was the text editor I used for this project.
* [Git](https://www.gitpod.io/)
  * Git is used as version control software to add, commit and push code to my GitHub repository where the code is then stored.
* [GitHub](https://github.com/)
  * I have used GitHub as a remote repository to push and store the committed changes to my project from Git.
* [jQuery](https://en.wikipedia.org/wiki/JQuery)
  * jQuery was used to initialize Materialize and for some of the sites functionality.
* [Google Chrome Developer Tools](https://developer.chrome.com/docs/devtools/)
  * I have used Google chromes built in developer tools to help with the styling of the site, selecting colors and to help fix any bugs I found.
* [Heroku](https://www.heroku.com/)
  * Heroku has been used to deploy my live site.
* [Flask](https://flask.palletsprojects.com/en/2.0.x/)
  * Flask was used as the web framework for the application.
* [MongoDB](https://www.mongodb.com/) 
  * MongoDB was used to hold the database for my project.
* [Werkzeug](https://werkzeug.palletsprojects.com/en/2.0.x/)
  * Werkzeug was used for password hashing and authentication.
* [Jinja](https://jinja.palletsprojects.com/en/3.0.x/)
  * Jinja templating language was used to simplify and display backend data in HTML.
* [Google Fonts](https://fonts.google.com/)
   * Google fonts were used to import the 'Poppins' font into the style.css file which is used on all pages throughout the project.
* [Am I responsive](http://ami.responsivedesign.is/)
    * This was used to check responsiveness on different screen sizes and create the showcase image for the project.
* [Google Lighthouse](https://developers.google.com/web/tools/lighthouse)
   * Google lighthouse was used to test the performance of my site.
* [The W3C Markup Validation Service](https://validator.w3.org/)
   * The validation tool to check for HTML errors.
* [The W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
   * The validation tool to check for CSS errors.
* [Color contrast](https://wave.webaim.org/report#/https://tararhoseyn.github.io/CardiffSwimCentreMS1/)
   * Color tool used to compare colors for the website.
* [Online JavaScript Beautifier](https://beautifier.io/)
   * Tool to help format the javascript code
* [Python Beautifier](https://codebeautify.org/python-formatter-beautifier)
   * Tool used to help format the python code
### Testing 

## CSS Validation
 * To test my CSS code I used the [The W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
 * There were no issues found
 ![CSS Validation](assets/CSS-valid-22-png)

## HTML Validation
 * To test my HTML code I used the [The W3C Markup Validation Service](https://validator.w3.org/)
 * There were no issues found

 ## Pep8 validation
  * To test my python code I used the [pep8 Validator](http://pep8online.com/)
  * There were no issues found

## Lighthouse testing
* I ran my pages through the google lighthouse tester to check the performance of my pages. The results can be seen in the images below. The results were overall pretty good with most of the scores being 90 and above. With performance getting 100 on four out of the five pages tested. The score that seemed to generate the lowest mark overall was accessibility. Upon invesitgation, it seems the white background was causing this issue. I have noted in my the future features section to adjust the white background in the future.

* Register page
![Register page](assets/lighthouse-register.png)

* Login page
![Login page](assets/lighthouse-login.png)

* Home page
![Register page](assets/lighthouse-home.png)

* Profile page 
![Register page](assets/lighthouse-profile.png)

* New task
![Register page](assets/lighthouse-addtask.png)

* Manage Categories
![Register page](assets/lighthouse-categories.png)


### Performance
 * Google Lighthouse was used to measure the performance and speed of the website.

### Responsiveness
 * The website was tested using the 'inspect' option available on Google and Internet explorer for different screen sizes and mobile. The following devices showed zero errors with responsiveness or format.
* **Devices:**
   * Samsung Galaxy S20
   * iPhone X
   * iPhone 11
   * Lenovo IdeaPad S340-14IIL
   * Samsung A70

### Accessibility
 * Google Lighthouse gave the website a score of XY% accessibility for both desktop and mobile

### Known Issues and Bugs
* Sometimes the text overlaps with the font awesome icon and a line - refreshing the page resolves this. A fix is being worked in. 

### Deployment

**Creating Repository:**
1. I created the repository using the following steps:
2. I logged into my GitHub account and clicked the green button near the top left of the page displaying the text 'NEW'.
3. This took me to a page with the option to create a new repository. Under the repository template I clicked on the code institute template. 
4. I chose a name for my repository and then clicked the create repository button.
5. I opened the new repository and clicked the green gitpod button to create a new workspace in Git Pod for writing and editing my code to develop the website.

### GitHub pages

**My project was deployed to GitHub pages using the following steps:**

1. I logged in to my GitHub account and opened the relevant repository.
2. I clicked on the settings button.
3. In settings I scrolled down to the GitHub 'pages' tab.
4. Under source I clicked the dropdown button labelled 'None' and selected Master Branch.
5. This then provided mw with the link to the website.

### Forking the GitHub Repository
1. Log in to GitHub and locate the [GitHub Repository](https://github.com/vanessacleary/vanessacleary-Ms1-2021)
2. At the top of the Repository just above the "Settings" Button on the menu, locate the "Fork" Button and click.
3. This will provide you with a copy of the original repository in your GitHub account.

### Making a clone
1. To make a clone of my project use the following steps.
2. Go to my account and locate the relevant repository.
3. Next to the green Gitpod button, click on CODE.
4. Click on Download Zip.
5. Once downloaded, you can extract the zip file's contents and save to a desktop and run the website locally.

### Deploying to Heroku
1. Log in to Heroku, click 'New' and select 'Create New App'. 
2. In the window give the app a name and choose the region closest to you and then click 'Create App'.
3. In the new app page select settings from the menu, click reveal config vars and complete the config variables.

### Credits
 * Code and Content
    * Materialize was used for the structure and layout of the site.
    * Google was used to find the images selected for the site.
    * Stackoverflow was used to help find solutions to the issues I had whilst building my project.
   * Code Institute mini task project was used a lot throughout the project to help with functionality across the site. 

### Acknowledgements
* Code Institute for providing endless help and resources to get me this far.
* Code Institute tutor support for pushing me and always supporting.
* My mentor Reuben Ferrante for the help and patience to guide me through my first data centric project.
* The Mini Feb 2021 group, wider slack community and the tutors for all the help, support and feedback for the last couple of weeks. 
* Friends and Family who have taken their time to offer advice and feedback during the development of my project.


