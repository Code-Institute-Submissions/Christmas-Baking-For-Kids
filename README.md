<div align="center">
<img src="https://i.ibb.co/7khKrDD/gingerbreadmen.jpg" href="https://christmas-baking-for-kids.herokuapp.com/" target="_blank" rel="noopener" alt="Christmas Baking for Kids"
    aria-label="Christmas Baking for Kids" />
</div> 

## Introduction

<div align="center">
    <img src="https://i.ibb.co/whcvV9B/home-page.png" href="https://christmas-baking-for-kids.herokuapp.com/" target="_blank" rel="noopener" alt="Image of how the home page will look on all screen sizes" aria-label="Image of how the home page will look on all screen sizes" />
</div>
<br>

[Christmas Baking](https://christmas-baking-for-kids.herokuapp.com) was created by Lee-Ann Clark. For all the parents who love baking and who enjoy sharing the kitchen with kids who like to experement and find their own way in the world of baking.

As a single mom who has a very industrious daughter, finding new things to make, bake and try is always a challenge. Having easy to follow recipes which are fun to make and delicious to eat, keeps young minds busy.
Being a mom who travels to different countries, adding new and exciting recipes that can be accessed easily adds new exciting choices for baking.

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
    - [Flowchart](#flowchart)
    - [PDF](#pdf)

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
    - [Collections Data Structure](#collections-data-structure)
        - [Users Collection](#users-collection)

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

7.  As a user accessing this site from smaller devices such as a mobile phone or tablet, I want the site to be responsive so that it is still easy to navigate. 


