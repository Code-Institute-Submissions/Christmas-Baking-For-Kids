<div align="center">
<h1>Christmas Baking For Kids</h1>
<img src="https://i.ibb.co/7khKrDD/gingerbreadmen.jpg" height="300px" href="https://christmas-baking-for-kids.herokuapp.com/" target="_blank" rel="noopener" alt="Christmas Baking for Kids"
    aria-label="Christmas Baking for Kids" /><br>
</div> 
<br>

[Christmas Baking](https://christmas-baking-for-kids.herokuapp.com) was created by Lee-Ann Clark. For all the parents who love baking and who enjoy sharing the kitchen with kids who like to experement and find their own way in the world of baking.

As a single mom who has a very industrious daughter, finding new things to make, bake and try is always a challenge. Having easy to follow recipes which are fun to make and delicious to eat, keeps young minds busy.
Being a mom who travels to different countries, adding new and flavorsome recipes that can be accessed easily adds new exciting choices for baking.

## Table of Contents
1. [UX](#ux)
    - [Goals](#goals)
        - [Visitor Goals](#visitor-goals)
        - [Business Goals](#business-goals)
        - [Christmas Baking For Kids Goals](#Christmas-Baking-For-Kids-goals)
    - [User Stories](#user-stories)
        - [Visitor Stories](#visitor-stories)
    - [Design Choices](#design-choices)
    - [Wireframes](#wireframes)
    
2. [Features](#features)
    - [Existing Features](#existing-features)
        - [Elements on every Page](#elements-on-every-page)
        - [Home Page](#home-page)
        - [Recipes Page](#recipes-page)
        - [Login Page](#login-page)
        - [profile Page](#profile-page)
        - [Add Recipe Page](#add-recipe-page)
        - [Log Out page](#logout-page)
        - [404 Page](#404-page)
        - [500 Page](#500-page)
    - [Features Left to Implement](#features-left-to-implement)

3. [Information Architecture](#information-architecture)
    - [Database choice](#database-choice)
    - [Data Storage Types](#data-storage-types)

4. [Technologies Used](#technologies-used)

5. [Testing](#testing)

6. [Deployment](#deployment)
    - [Heroku Deployment](#heroku-deployment)
    - [How to run this project locally](#how-to-run-this-project-locally)

7. [Credits](#credits)
    - [Content](#content)
    - [Media](#media)
    - [Code](#code)
    - [Acknowledgements](#acknowledgements)

8. [Disclaimer](#disclaimer)

----

# UX

## Goals

### Visitor Goals

The target audience for Christmas Baking for kids is:
- Families with children aged from 6 up who love to be in the kitchen.
- Grandparents who want to spend time sharing family recipes with their grandkids.
- Anyone who enjoys baking and wants to add and store their own recipes online.
- To be able to add a recipe and have family access it in another country.

User goals are:

- To have a place to keep new and old family recipes, without them getting lost.
- To be able to access your recipes easily and from anywhere in the world.
- To be able to grow your own profile of recipes and print out your own family recipe book
- To be able to try new recipes from other families and watch the recipe book grow.

Some extra goals users might have.
- Be inspired and join a baking class or demonstration.
- Spend more quality fun time with their kids in the kitchen.
- Teach kids about ingredients and where to buy them.
- Go and explore the nearby shops for ingredients for your new recipes.

Christmas Baking For Kids meets these user needs in that:

- The recipes here are family favorites. They can be added to, edited or even deleted all under your profile.
- As the recipes are online, they can be accessed from anywhere, world wide.
- With every new user, there are new recipes and the book is ever changing. 
- This is wonderful in that there are always new and improved ideas to try and recipes to inspire all bakers.

### Business Goals

- To give the user the option to have their profile of recipes printed- A hard copy Recipe Book (brilliant for coffee table or gifts).
- Being online means world wide audiences- baking equipment, demonstrations and classes to be incorporated( future aspects).
- Growth from baking into other areas of food- parties,catering equipment, special functions.
- A Recipe book to cover all.

Business user goals are:

- A great gifting idea-To have a family Recipe book printed( This is how the site can be moniterized)
- A user-friendly design that reaches out to both parents and children
- The user interface is easy to use and the input of data is done in a efficient manner.

Christmas Baking For Kids meets these user needs in that:

- The login page provides the user access to the recipe book to be able to add their own recipes. The user interface for the input on this page is carefully controlled in that
  the user has to add a user name and password, both of which are required to move forward.
- The profile page shows the user his/her recipes that have been added. The user also has the option to go back into their own profile and edit or delete their own recipes.
- The Add-Recipe page clearly structured and laid out in an easy to understand way.The user has the option to Add their Recipe, if they are satissfied they can
  then save their recipe or delete it.
- The user interface for the input of recipe data on the add-recipe page has been controlled to validate input. For example the correct url format is required for the image input.
  The fields for name of recipe and recipe ingredients and method are required so that information needs to be added correctly.
  Setting input field types to `minlength`, `maxlength`,`number`, `url` etc makes sure the user is prompted when the data they have added is incorrect.

- The recipe page then shows the user all listed recipes including their own. 

- To make navigation easy for the user, buttons have been provided on the pages to help direct should they get stuck. For example, cancel, edit, add-recipe etc.

### Christmas Baking For Kids Goals

- To provide a fun and easy to use site for familys to search, store and retrieve their special recipes.
- To be able to find inspiration in newley added recipes
- So that I as a student can learn and practice frontend and backend programming together for the first time. To combine the use of HTML, CSS, Materialize and JQuery with Python, MongoDB, Flask and Jinja.

## User Stories

### Visitor Stories

As a visitor to Christmas Baking For Kids I would expect/want/need:

1. To easily find what I am looking for, I want the site layout to make sense, as varing ages have varing understanding so I dont want to be confused or put off using it. 

2. The information to be laid out in a way that is easy for me to navigate and understand, so I may find what I need quickly and efficiently.

3. The ability to search through the recipes to find what I need. Then to be able to click and get more detailed information.

4. To be able to filter the recipes by name, method, ingredients and find the recipes that are best suited for my needs.

5. As a parent I want to be able to find a recipe that is easy and quick and fun to make.

6. As a parent I want my child to enjoy choosing the recipes and understanding the instructions.

7. As a user accessing this site from smaller devices such as a mobile phone or tablet, I want the site to be responsive so that it is still easy to navigate. 

## Design Choices

Christmas Baking For Kids has a Christmas and family friendly feel to it. The emphasis was on providing easy to follow information in an understandable way for any age group. 
The following design choices were made with this in mind:

### Fonts

 The primary font `Playfair Display` was chosen for the main text on the site as it is easy to read both when printed and in cursive. 
 The site will have all age-groups reading it so the printing needs to be clear and easy to understand.

### Colours
<div align="center">
    <img src="https://i.ibb.co/Xpm5Nf5/color-palette.png" alt="Christmas Baking Color Palette" aria-label="Christmas Baking Color Palette" />
</div>
Being a Christmas recipe book, Green is the color I chose. It is easy on the eye and goes with all images that are added.

- The navbar background colour is a soft green colour, dark enough to provide contrast with the white headings, while darkening to a darker green when hovering over the nav links.
- The Welcome heading is done in Green which stands out on the crips white background of the page.
- The category cards have clear black writing on them and a link to their page at the bottom of the card with a green background.
  The writing in the green background turns white when you hover over it.
- In the footer a green was again used, setting the footer apart from the rest of the content. The writing in the footer is an off white which is easy on the eye. The base of the footer
  where the copy right is has a darker green to make it stand out a little more. 

### Styling

- All **buttons** on the site fit the materialize button styling in size and shape, I kept the colors of green red and blue for the Christmas theme. 
- Materialize **cards** were utilized on the home page to display the category selection, with a link to each category selection page on it. 
- hover effects
    - Some subtle **shadows** have been added to the nav bar and category cards, to give them depth on the page. The **color-change** on the navbar 
    on hover, gives the user a positive user experience in highlighting the section of the site they are hovering over.


## Wireframes





# Features
 
## Existing Features

### Elements on every page
- Navbar
    - The navigation bar features the Christmas Baking For Kids logo in the top left corner.

    - For visitors to the site who are not logged in, list items links are available for them to use.
        1. Home (The logo itself)
        2. Recipes (drop down menu of categories)
        3. Log In
        4. Register 

    - For users who are logged in, the list items are as follows: 
        1. Home (The logo itself)
        2. Recipes (drop down menu of categories)
        3. Profile
        4. New Recipe
        5. Log Out

- Python determines if the user is logged in or not by checking `if 'user' in session` and passes this data to Jinja to display the correct welcome message on the profile page to the user.
- The navbar is collapsed into a burger icon on small and medium screens, so that menu items do not start overlapping content or headings. 

- Footer
    - The footer features:
        - A list of category links users might need when viewing the footer and wanting to return to a perticular page.
        - A thank you message. 
        - Copyright information.

### Home Page

**Hero Image**
- The Christmas Baking For Kids home page features a cheerful and colorful hero image of every childs favorite. Gingerbreadmen. I chose this image because when you see gingerbreadmen you think of christmas and the kids love making them.
  This image is coded as a background-image in css and set to `background-size: cover;` so that it is responsive and doesnt distort or stretch. 

**Horizontal Cards**
- Each horizontal card on the home page gives the user some idea of what categories they will find. There is am image of the category, for example biscuits and next to it a little verse relating
  to the category. Below this is a link to the page should you decide to go to that perticular category from the horizontal card.

**Footer**
- The footer is in the same shade of green as the navbar with a darker shade of green for the copyright at the bottom of the page. There is a little thank you message to the user and the hope that they added some recipes.
  There is a Quick links section so that you can return to any of the category pages should you choose from the footer itself. The footer appears at the base of all pages.

### Recipes Page
<div align="center">
<img src="https://i.ibb.co/f8NmPtq/Recipes-Page.png" alt="Christmas Baking For Kids Recipes Page page on all major screen sizes" >
</div>
<br>
**Dropdown List**
- This dropdown list is found in the navbar. It is a dropdown list of all categories of recipes found in the recipe book.At the top is `ALL`, then `Biscuits`, `Sweets`, `Cupcakes` and then `Desserts. 
  Each selection takes you to the recipe page of all recipes added in that category in the book.

**Search Bar**
- On the top of each recipe page is a Search Bar that was coded in using `Text Index Searching`. The search bar has a search button and a reset button on the left side of the search bar.
  The user can search through a set of parameters such as `Recipe Name` and  `Ingredients` to find their favorite recipe.

**Horizontal Recipe Cards**
- Each horizontal recipe card on the recipe page whether it is for ALL recipes or a perticular category have the same layout. They have the green that is consistent throughout the site as a background for 
  the recipe name. The card then has an image that expands when clicked on and is coded as `Materialboxed` from materialize. Next to the image is the `Cooking Time` for the recipe. Below this is the information of who added the recipe. `Added By` 
  and then the card also gives the information of who the recipe is credited to. `Credit To`.

### Log In Page
<div align="center">
<img src="https://i.ibb.co/yY2ksXm/Login-Page.png" alt="Christmas Baking For Kids Login Page page on all major screen sizes" >
</div>
<br>
- The log in page features a simple **form** where the user enters their username and their password. If the user enters an incorrect password or username a flash message will inform the user of this.
  The user once logged in will recieve a welcome message and be directed to their profile page. 
- The profile page a page for that spercific user. All the recipes that this user has ever added will be on this page. This page is unique to the user.
- The user has the option on this page to edit or delete recipes. These buttons will appear on only the session users profile page on the recipes. The user will not be able to edit or delete recipes that 
  were not added by the user themselves.
- If the user does not have a username or password the user is directed to the register page.

**Register Page**
- The Register page is also a simple **form** where by the user has to choose a username and password. Once the user name and password have been entered and are not duplicates of what is already there, the 
  site will direct you to your blank profile page. Now you are ready to start adding recipes.

**New Recipes**
<div align="center">
<img src="https://i.ibb.co/XtgpJ6c/Add-Recipe.png" alt="Christmas Baking For Kids Add Recipe Page page on all major screen sizes" >
</div>
<br>
- This can only be accessed if you are logged in as a user.
- The New Recipes page is a **form** that gives the user the selection of which caregory they want the recipe to show in. The user then has to correctly insert the image URL for their recipe. This has been tested
  so that the input needs to be correct otherwise a **404** page will appear.
-The user then needs to complete the cooking time, how many the recipe makes and then all the ingredients and the method need completing. They can then add their name to the recipe and hit the `Add Recipe` button 
  at the bottom of the page. Upon succsessful upload of the recipe a message will show saying the recipe was successfully uploaded.
- Validation of the `<input>` fields is handled in different ways.The input `type` attributes are set to `text`, and `url`.
- Limits are placed on both min and max lengths of input accepted.<br>

**Editing Recipe**
- Once a new recipe has been added and the user wants to edit his /her recipe, they can log in to their profile page and on their recipes will be 2 buttons.
  One for `Edit` and the other for `Delete`. The edit button allows the user to edit the recipe. Upon successful completion a message will state that the recipe
  has beed successfully edited and the user is returned to the recipe page. Should the user decide that they want to **DELETE** the recipe and they click on deletd,
  a modal will appear with a message asking if the user is sure that want to delete this? if the user clicks on the "Yes" button below the recipe will be deleted. If they 
  click on the "NO" button the client is returned to the edit page.

### 404 Page

### 500 Page

## Features Left to Implement

Admin account 
- Give myself (or any other administrator of Christmas Baking For Kids) special permission to access and or change data in the database from a Christmas Baking For Kids interface, 
  rather than having to access the data directly in MongoDB.
- Give admin the ability to view, edit and delete any Recipe from database.

The Features Left To Implement is a section that will grow in time as the site itself grows.

# Information Architecture

### Database Choice

As this website is a student project and where i am in the course my only opportunity is use NoSQL. 
In order to gain experience in using NoSQL this project uses the NoSQL database MongoDB. 
Easy access to relational data was made possible as inner objects were used inside the data structure so it could be easily accessed and looped through where needed.

### Data Storage Types

The types of data stored in MongoDB for my project are:
- ObjectId
- String
- Boolean
- Object

# Technologies Used

### Tools
- [Gitpod](https://www.gitpod.io//) is the IDE used for developing this project. 
- [Imgbb](https://imgbb.com) to store all external images for this project.
- [Git](https://git-scm.com/) to handle version control.
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) is the database for this project
- [GitHub](https://github.com/) to store and share all project code remotely. 
- [Browserstack](https://www.browserstack.com/) to test functionality on all browsers and devices.
- [Techsini](http://techsini.com/) to create the images in this readme file of each page displayed on different screen sizes.

### Libraries
- [JQuery](https://jquery.com) to simplify DOM manipulation.
- [Jasmine](https://jasmine.github.io/) to run automated tests on JavaScript and jQuery code.
- [Jasmine-jQuery](https://github.com/velesin/jasmine-jquery) to make it possible to test jQuery code using Jasmine.
- [Materialize](https://materializecss.com/) to simplify the structure of the website and make the website responsive.
- [FontAwesome](https://fontawesome.com/) to provide icons for this site.
- [Google Fonts](https://fonts.google.com/) to style the website fonts.
- [PyMongo](https://api.mongodb.com/python/current/) to make communication between Python and MongoDB possible.
- [Flask](https://flask.palletsprojects.com/en/1.0.x/) to construct and render pages.
- [Jinja](http://jinja.pocoo.org/docs/2.11/) to simplify displaying data from the backend of this project smoothly and effectively in html.

### Languages
- This project uses HTML, CSS, JQuery and Python programming languages.

# Testing 

## Programs used for testing

- [Sauce Lab](https://saucelabs.com/) Automation Testing.
    - Sauce Lab report [here](https://i.ibb.co/VW5wkN6/cross-browser-test.png)
    - I logged in to Sauce Labs and ran the test on each browser to see how the website faired.
      The report came back with no errors on any of the browsers.


- [Perfecto](https://testingcloud.app.perfectomobile.com/) Manual Mobile Testing
    - Perfecto manual testing report [here](https://i.ibb.co/KmNnBjY/mobile-phones-tested.png)
    - I logged into Perfecto and manually selected the mobile devices to run the tests on.
        - On each device i entered Christmas Baking For Kids URL, on all devices chosen it logged in.
        - I then mannually selected the links for the categories to see if they all went to the correct pages.They did.
        - I logged in as a returning user tested the password and username to see if they worked , no errors.
        - I registered as a new user to see that the username and password worked. No errors.


# Deployment

## How to run this project locally

To run this project on your own IDE follow the instructions below:

Ensure you have the following tools: 
- An IDE such as [Gitpod](https://gitpod.io/)

The following **must be installed** on your machine:
- [Python 3](https://www.python.org/downloads/)
- [Git](https://github.com)
- An account at [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) or MongoDB running locally on your machine. 
    - How to set up your Mongo Atlas account [here](https://docs.atlas.mongodb.com/).

### Instructions
1. Save a copy of the github repository located at https://github.com/Lee-AnnC/Christmas-Baking-For-Kids by clicking the "download zip" button at the top of the page and extracting the zip file to your chosen folder.
   If you have Git installed on your system, you can clone the repository with the following command.
```
git clone https://github.com/Lee-AnnC/Christmas-Baking-For-Kids
```

2. If possible open a terminal session in the unzip folder or cd to the correct location.

3. A virtual environment is recommended for the Python interpreter, I recommend using Pythons built in virtual environment.

Enter the command:
```
python -m .venv venv
```  
_NOTE: Your Python command may differ, such as python3 or py_

4. Activate the .venv with the command:
```
.venv\Scripts\activate 
```
_Again this **command may differ depending on your operating system**, please check the [Python Documentation on virtual environments](https://docs.python.org/3/library/venv.html) for further instructions._

4. If needed, Upgrade pip locally with
```
pip install --upgrade pip.
```

5. Install all required modules with the command 
```
pip -r requirements.txt.
```

6. In your local IDE create a file called `.flaskenv`.

7. Inside the .flaskenv file, create a SECRET_KEY variable and a MONGO_URI to link to your own database. 

8. You can now run the application with the command
```
python3 app.py
```
9. Remember to /load_categories to be able to see the recipe categories

## Heroku Deployment

To deploy Christmas-Baking-For-Kids to heroku, take the following steps:

1. Create a `requirements.txt` file using the terminal command `pip freeze > requirements.txt`.

2. Create a `Procfile` with the terminal command `echo web: python app.py > Procfile`.

3. `git add` and `git commit` the new requirements and Procfile and then `git push` the project to GitHub.

3. Create a new app on the [Heroku website](https://dashboard.heroku.com/apps) by clicking the "New" button in your dashboard. Give it a name and set your region to Europe.

4. From the heroku dashboard of your newly created application, click on "Deploy" > "Deployment method" and select GitHub.

5. Confirm the linking of the heroku app to the correct GitHub repository.Make sure this is your Repository name.

6. In the heroku dashboard for the application, click on "Settings" > "Reveal Config Vars".

7. Set the following config vars:

| Key | Value |
 --- | ---
DEBUG | FALSE
IP | 0.0.0.0
MONGO_URI | `mongodb+srv://<username>:<password>@<cluster_name>-qtxun.mongodb.net/<database_name>?retryWrites=true&w=majority`
PORT | 5000
SECRET_KEY | `<your_secret_key>`

- To get you MONGO_URI read the MongoDB Atlas documentation [here](https://docs.atlas.mongodb.com/)

8. In the heroku dashboard, click "Deploy".

9. In the "Manual Deployment" section of this page, made sure the master branch is selected and then click "Deploy Branch".

10. The site is now successfully deployed.

# Credits

## Content

- The text, images, links and other data in the database was sourced from various websites including but not limited to

    - [Kitchen Warehouse](https://blog.kitchenwarehouse.com.au)
    - [Taste](https://www.taste.com.au/)
    - [Like Mother Like Daughter](https://lmld.org)
    - [Favorite Family Recipes](https://favfamilyrecipes.com)
    - [Artful Parent](https://artfulparent.com)
    - [Your Cup Of Cake](https://www.yourcupofcake.com)
    - [Olive](https://olivemagazine.com)
    - [Laura loves cakes](https://lauralovescakes.blogspot.com)
    - [Two Sisters](https://www.twosisterscrafting.com/)
    - [A Table Full Of Joy](https://www.atablefullofjoy.com)

- All other text on Christmas Baking For Kids site was written by me.

## Media

### Images

- The photograph for the hero image was sourced from [Delish](https://www.delish.com)

- Where possible the links to the images for the recipes were taken directly from the source image url. 

- On occasion when this did not work the image was copied to my local machine and then uploaded to my [imgBB](https://leec.imgbb.com/) account, where I took the link from instead.

## Code

- Template code for this site was taken from our Task Manager Mini Project Lessons and heaverly modified to suit the site needs.

- Template code for horizontal-cards in the recipes taken from [Materialize](https://materializecss.com/cards.html) and modified to suit the sites needs.

- Code for buttons taken from [Materialize](https://materializecss.com/buttons.html).

- Code for the grid was taken from [Materialize](https://materializecss.com/grid.html)

- Code for adding the correct prefixes to css was created using [AutoPrefixer](https://autoprefixer.github.io/).

## Acknowledgements

Special thanks to my mentor **Aaron Sinnot** for his patience and help and for listeningto my never-ending questions.

Special thanks to **Malia Havlicek** whos patience and understanding has helped in many a dark day when things haven't gone to plan.

## Disclaimer
This is a student project and hence the content of this website is educational purposes only.
