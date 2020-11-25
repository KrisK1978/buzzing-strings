## Table of Contents
- [Project Goal](#project-goal)
    - [Designer Strategy](#designer-strategy)
    - [Design Elements](#design-elements)
    - [Wireframes](#wireframes)

- [Features](#features)
    - [Features to be implemented in the future](#features-to-be-implemented-in-the-future)

- [Technologies used](#technologies-used)
    - [Other sources used to build the project](#other-sources-used-to-build-the-project)

- [Testing](#testing)

- [Project deployment](#project-deployment)
    - [Local deployment](#local-deployment)
    - [Heroku deployment](#heroku-deployment)

- [Project database structure](#project-database-structure)
    - [Schema](#schema)

- [Credits](#credits) 
    - [Contents](#content)
    - [Media](#media)
    - [Inspiration and motivation](#inspiration-and-motivation)
    - [Acknowledgements](#acknowledgements)

- [Disclaimer](#disclaimer)


## Project Goal
The main goal for creating this website is to deliver interesting information about different type of guitars. This website 
is not only recommended for guitarists who would like to check/add/review the guitars they like, but to any website user who 
would like to gain more knowledge about this fantastic instrument. 

### Designer's Strategy
- to create a website which will be a user-friendly and easy to navigate;

- to deliver a website with easy to read, informative, concise text which will play a major role in search engine placement;

- to create a website which engages its users and continues to hold their attention when they browse through it;

- to provide a simple information accessibility and place key information in a plain manner, so the users can only locate  
 a certain bit of info i.e. register form, social-media links, etc., without perusing the entire site;

- to create a website which will be intuitive and would anticipate the users' needs;

### Design Elements

### Wireframes
The wireframes can be found [here]().

## Features

### Features to be implemented in the future

## Technologies used

### Other sources used to build the project

## Testing
The project testing details can be found [here](https://github.com/KrisK1978/buzzing-strings/blob/master/TESTING.md).

## Project deployment 

### Local deployment

#### Additional information

### Deployin and app to Heroku 
Use the following steps to deploy [buzzing-strings]() to Heroku:

1. Create a **requirements.txt** file using the command below:

    `pip3 freeze --local > requirements.txt`

2. Create a **Procfile** file using the following command:

    `echoweb: python app.py > Procfile`

    - *make sure it is a capital P and there is no file extension added*
    - *open a Procfile file and remove a blank line as if left it can cause problems with an app*

3. Push new created files to **GitHub** repository.
4. Go to [Heroku](https://id.heroku.com/login) and create a new app for this project using **Heroku Dashboard**.
5. Remember to give your app a unique name and set up a region.
6. In **Deployment** tab go to **Deployment Method** and click on **GitHub** icon to connect an app. Type in 
   *repository name* and hit *search*. Once repository is found click **Connect**.
7. Go to **Settings** tab and open **Config Vars**. Add the following information:

    |   **Key**         |                             **Value**                                                       |
    | ----------------- | ------------------------------------------------------------------------------------------- |                        
    |       IP          |                              0.0.0.0                                                        |
    |      PORT         |                              5000                                                           |
    |   MONGO_DBNAME    |                         'database name'                                                     |
    |    MONGO_URI      | mongodb+srv://:@<cluster_name>-qtxun.mongodb.net/<database_name>?retryWrites=true&w=majority|           
    |   SECRET_KEY      |                           'secret_key'                                                      |


8. Go back to **Deploy** tab and scroll down to find **Automatic Deploys**. Click on **Enable Automatic Deployment**.
9. Remember to click **Deploy Branch** as we have only one branch for this project. **Heroku** will receive the code from
   **GitHub**. When new changes are pushed to **GitHub** next time, our app content should be updated accordingly. 


## Project database structure

## Credits 

### Contents
The content of the website was written by me. 

### Media 
I used the following media platforms to complete this project:

- [Guitar Guitar](https://www.guitarguitar.co.uk/)

- [Kenny's Music](https://www.kennysmusic.co.uk/)

- [Gear4Music](www.gear4music.com)

- [Traversy Media](https://www.traversymedia.com/)

### Inspiration and motivation 
[Guitar Guitar](https://www.guitarguitar.co.uk/) and my friend Dawid, a fantastic guitarist, was my main inspration to build [buzzing-strings]() website. 
I have always considered a guitar as one the most magical instruments in music history. I had a great opportunity to 
see some fantastic guitarists in my life and was able to admire how a sound connection can be built between an instrument and a human.
My motivation was not only to highlight the fact how great this instrument is but also to give an opportunity to the website users to share
their thoughts about their favourite guitars. I was also motivated to deliver some interesting facts/information to users who never played a guitar,
but would like to gain some knowledge about this instrument. 

### Acknowledgements
This project would not be completed without a great support of my family and friends and my mentor [Simen Daehlin](https://github.com/Eventyret).
Their constructive advice delivered valid and well-reasoned opinions. It involved both positive and negative comments which helped 
me to see my project from a different perspective and amend the content to achieve the ultimate goal, a user-friendly and
interesting website. 

Also, I would like to thank my fellow [Code Institute](https://codeinstitute.net/) students and tutors who always been there for me, 
offering a friendly advice when I was having problems with sorting things out. Last but not least [Slack](https://slack.com/signin#/signin) 
community which I found extremely helpful in resolving code-related issues. 

### Disclaimer  
This website was created for educational purpose only.

[Back to top](#table-of-contents)