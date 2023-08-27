![Alt Screenshots](../CFG-SoftwareTeam7/app/static/Assets/KokoroZen_logo.svg)
​

## Introduction

KokoroZen is a virtial pet wellness app. This web application merges the joy of caring for a virtual pet with the importance of self-care. Users can nurture a virtual character while exploring various self-care activities, transforming self-care into an engaging journey.
​
## Project Objectives

Provide a playful and interactive app in the form of a virtual pet to take care of to motivate users to prioritise their well-being. Users nurture a virtual character through completing self-care activities.

Encourage frequent use through an easy to use and visually appealing user experience, transforming self-care into an engaging journey holding users accountable.
​
​

## Screenshots

​
![Alt Screenshots](../CFG-SoftwareTeam7/app/static/Assets/KokoroZen-Home.png)



## Key Features

- Health & Happiness Tasks: KokoroZen helps users create a to-do list that affect their health an happiness.

- Pet Health & HappinessBars: By logging and completing tasks, the virtual pet's health percentage increases. Leave tasks too long or delete them, the health goes down.

- Motivational Quotes & API Integraton: Users can click on the pet's heart button for an inspirational quote and mental health "pick-me-up" that adds to the pet's health bar percentage. The action triggers an API call using API Ninja's Quotes API to access a motivational quote.

- Food, Drink & Exersize Buttons: Users can quickly log when they have drank water, eaten healthy, or exersized with the pet's buttons. When clicked they add to the pet's health bar percentage.

- Register or Log In: Users can register as a new user and create their own account using a username, email address, and secure password.

- User Sessions: Users sessions are saved so they can come back any time to log new tasks, complete, delete, or edit tasks.

- Secure Data Storage: User profiles and data are stored in a secure MySQL database.
  ​

## Installation

To set up and enjoy KokoroZen, use the following steps:
​

1. Clone the repository to your local machine:
   ​

   ```bash
   git clone git@github.com:waterzaddy/CFG-SoftwareTeam7.git
   ```

2. Install dependencies
   ```bash
   pip install flask
   pip install flask-sqlalchemy
   pip install unittests
   pip install requests
   pip install apscheduler
   ```

## Run the app

1. For a smooth experience, please use VS Code or PyCharm, MySQLWorkbench and of course Chrome as your browser.

2. Navigate to the folder of the cloned repository on your local machine, navigate to the app.py file in the app folder and open it in PyCharm or VS Code. 

3. Navigate to the project directory:
​
    ```bash
    CFG-SoftwareTeam7
    ```

4. Open mySQL, connect to your local instance.

5. Run the script in XXXXXX.sql ensuring that the database has been created and is being used

4. Open app.py from the src folder and edit this line:

   DATABASE_URL = 'mysql+pymysql://root:YOUR_PASSWORD_HERE@localhost/Smart_Eats_db' with your local host password

5. Using Terminal, run app.py, this will create a link to copy into Chrome where the homepage will load.​

## How To Use

- Register or Login
- Populate the Heath and Happiness To-Do lists with tasks you wish to accomplish
- Complete tasks to add to your Pet's health
- Quickly log eating healthy, drinking water or exercising by pressing the buttons on the Virtual Pet.
- Get a motivational quote and add to your Pet's happiness by pressing the heart button
   ​

## Team Members


- Clara Londoño [@clgonzalez93](https://github.com/clgonzalez93)
- Elena Ailenei [@iberom0k](https://github.com/iberom0k)
- Kelli Garnett [@waterzaddy](https://github.com/waterzaddy)
- Sara Murray [@CosmicImprint](https://github.com/CosmicImprint)
- Zsannett Horvath[@zsannhorvath](https://github.com/zsannhorvath)
  ​
