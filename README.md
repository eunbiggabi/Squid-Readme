# T3A2 Part B (and Part A)

---
#### React-Rails Web App, developed by Eun Jeon(Kyu)
---

## R4. Demonstrate Ability to Work in Team

Part A was done as a group, but unfortunately Part B was done alone. Therefore, I only give a link to the github attributes of Part A.

https://github.com/jobitoalv/T3A2/graphs/contributors

Please see below - Part A

## R5. Produce a Working Application That Meets Client and User Needs

- Crud Actions
- Importing Image
- Three option choices of color
- Searching by name from Created Data
- User Auth

Please see app.

## R6. Deploy App to a Cloud Hosting Service
Deployed. Please check R10 below.

## R7. Produce an Application With an Intuitive User Interface

- Edit & Add Form
- Preview Section
- Search Bar 
- SignUp & LogIn Section

Please see app.

## R8. Provides evidence of user testing

#### In the development environment

| TYPE | TASK | OUTCOME | COMMENTS |
| :--: | :--: | :-----: | :------: |
| authenticate | user can sign up | fail | cannot able to create user
| authenticate | user can login | pass | only can log in with seed file data and navigate to /maker page|
| authenticate | user can log out | pass |
| intergration | get data from heroku | pass | initial data shows from seed file |
| card | add card | fail | data not save to back-end, but it is working on front-end |
| card | edit card | fail | data not save to back-end, but it is working on front-end |
| card | delete card | fail | data not save to back-end, but it is working on front-end |
| theme | choose color | fail | data not save to back-end, but it is working on front-end |
| image | upload | fail | 
| search | user can search by name | pass | able to search all the seed file data |
| search | user can see error message | pass | show up with red color error message |
| link | user able to access to all routes | pass | 
| display | user diplay | pass | try not to use fluorescent color |
| responsive | switch to mobile and tablet | pass | everything is responsive |


#### In the production environment
***this test done by my friends(Kim and Sammi)***

| TYPE | TASK | OUTCOME | COMMENTS |
| :--: | :--: | :-----: | :------: |
| authenticate | user can sign up | fail | not sure whether I sign up or not. Nothing shows up |
| authenticate | user can login | fail | not able to log in with what I create, but it is working with exsiting user |
| authenticate | user can log out | pass |
| intergration | get data from heroku | n/a | 
| card | add card | fail | looks working well, but everything return to original when I refresh |
| card | edit card | fail | looks working well, but everything return to original when I refresh |
| card | delete card | fail | looks working well, but everything return to original when I refresh |
| theme | choose color | fail | looks working well, but everything return to original when I refresh |
| image | upload | fail | it is clickable but can not save |
| search | user can search by name | pass | all searchable names are working well with theme colors |
| search | user can see error message | fail | error message still shows up after I found right searchable name |
| link | user able to access to all routes | pass |
| display | user display | pass | everything is clear and neat, also I like colors of website 
| responsive | switch to mobile and tablet | pass | everything is responsive |



## R9. Utilises a Formal Testing Framework

Please see app for Jest and Cypress on testing files.

## R10. A Link (URL) to Deployed Website

[Netlify](https://epic-curie-8e15c5.netlify.app)

[Heroku](https://kyusquid-api.herokuapp.com/api/cards)


## R11. GitHub repository

[Front-End](https://github.com/eunbiggabi/Squid-maker-app)

[Back-End](https://github.com/eunbiggabi/Squid-maker-api)


## R12. The contents of your README.md as submitted for Full Stack App - Part A

---
#### Documented by Eun Jeon(Kyu), Job Alvarez Chow, and 	Ethan Tran
---
***Note: Part A planning documentation is different from my actual outcome which is Part B***

***Part B documentation can be check from "PPL folder" which is problem solving, purpose, erd, wireframe and Challenges***


## R1 Description of your website, including:
****Purpose****

The main idea for "Squid Note" is to be able to make planning an event alot eaiser for people with no time and in a buget. 

there will be a keyword bar where you can type in what sort of event they are after. 

****Functionality / Features****

once a user logged in , the user will be able to create their own customised event planning board, first can seach for the event.

***Target Audience***

Our target audience are mainly for people who are new to planning events.

- Familys 
- Anyone on a buget 
- Group of friends 
- People with no idea where to start when it comes to planning an event.

This app will be good for people with no time to look around for everthing they will to plan an event . the app will be able to help them list out the items they need and places idea for their desire event. 

****Tech Stack**** 

The backend of the "Squid note" we will be using Ruby on Rails , set up in API mode . This will be integrated with Postgresql database and hosted on Heroku. Two Ruby gems will be incorporated to permit secure user logon knock (to generate the JavaScript web token for user authentication), and bcryot (to provide the password hashing algorithm).

The app will be completley free of charge, but in the future we might implement the payment gems (Stripe) for users to be able to make direct payment with us. 

The Front-end will utilise React.js, and be hosted on Netifly. It will communicate with the Rails API using HTTP client. the useState, useEffect, and useContext hooks will be utilized where applicable.

Testing will be performed using cypress.js.


## R2 Dataflow Diagram
![data flow1](https://i.imgur.com/l73NLz1.jpg)

Entity Relationship Diagram
![ERD](https://i.imgur.com/c7EBByU.png)


## R3 Application Architecture Diagram
![Architecture Diagram](https://cdn.discordapp.com/attachments/912503877725741107/915506465492590652/Application_architecture_diagram_1.png)



## R4 User Stories

User Expectations:

All users will expect the following features or functionality:

- It makes it impossible for users to use it unless they log in so that they can record their own events.

- The layout is designed so that you can recognize the events created by the user at a glance.

- Through search and filter, user can get suggestions for the items you want to find.

- It displays all the information you need to know through a dashboard familiar to the user.

- It makes it possible to quickly and easily create, view, update, and delete all event items.

- The number and cost of items in all products can be recorded and they are calculated.


User Characterisitics

Three distinct target user types were considered:

- Mark is going to choose his mother's birthday present. He was suggested a gift for his mother after choosing the age group and gender through the squid note. And he will make a list and think about what would be suitable.

- Here is a man named John who wants to marry his beloved girlfriend two months later. He wants to record simple plans and costs. In this case, he can search all the items and costs you need through squid note

- Chloe is an event planner. She needs an app that can manage various events. In this case, she can manage the lists you have recorded for each title along with the total cost.


## R5 WireFrames

- Pop Up
![Pop up](https://i.imgur.com/r0v3aGo.png)

- Sign Up
![Sing up](https://i.imgur.com/1WMAAYy.png)

- Home(Event Preview)
![Home](https://i.imgur.com/54VlvJV.png)

- Search 
![Search](https://i.imgur.com/h2nPULo.png)

- Filter
![Filter](https://i.imgur.com/nT8qza3.png)

- Edit
![Edit](https://i.imgur.com/wBq3XFW.png)

- View Detail
![View Detail](https://i.imgur.com/zFq25GE.png)




## R6 Screenshots of your Trello board throughout the duration of the project
Day 1.
![screen shot 1](https://i.imgur.com/qSD4LY5.png)
Day 2.
![Screen shot 2](https://i.imgur.com/wVKL0uB.png)
Day 3.
![Screen shot 3](https://i.imgur.com/Ojk2VHt.png)
