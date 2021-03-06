# Tradeful technical evaluation

##### The parameters of this evaluation:
    1. Create a Laravel Project.
    2. Push appropriate files to github/bitbucket.
    3. Create a route that display/update and create data in a database table
    4. Use a model
    5. Use Blade Template engine
    6. Create the relevant table as a migration
    7. Display, update and create front end for the data in a non-horrible looking way.
    8. The turn around time expectation is 1 week.

#### Project Documentation
 - Date received: 11/12/2020
 - Due Date: 11/19/2020
 - Project Description: I'm going to build a "Wheel of Fitness", to - hopefully - demonstrate adequate technical understanding and skills required for this role. 
 - Stack Description: Laravel framework using PHP, mysql, and the Blade templating engine. Git for source control hosted on Github. 

#### User Stories

    As a <parent>
    I want <a wheel of fitness>
    so that <I can play with my kids and get a little exercise>

    As an <applicant>
    I want <a test green suite>
    So that <I can demonstrate adequate understanding of behavior driven development>

#### Feature: Wheel of fitness

    Description: A directory of exercises, that can be randomly selected, along with randomized #s of sets & reps. Of course includes jackpots like hershey kisses, and land mines like burpies to failure

#### Acceptance tests (per the evaluation parameters, and my own)

    It would be acceptible if 
        Given a user is on the '/exercises' route
        When they c/r/u/d an exercise
        Then the app c/r/u/ds the data in a database table, per the Exercise model & its migration file(s)

    It would be acceptible if 
        Given a user is on the '/exercises' route
        When they look at the page
        They can honestly say, "This doesn't look horrible".
    
    It would be acceptible if 
        Given a user has cloned the repo
        When they run the test suite
        All tests should be green    

    It would be acceptible if 
        Given a user is on the '/exercises' route
        When they click the spin the wheel button, (or if i get there, actually spin the wheel) 
        Then they hear a click for each segment passing

#### Don't forget to:

    Rename .env.example file to .env inside your project root and fill the database information. (windows won't let you do it, so you have to open your console cd your project root directory and run mv .env.example .env )
    Open the console and cd your project root directory
    Run composer install or php composer.phar install
    Run php artisan key:generate
    Run php artisan migrate
    Run php artisan db:seed to run seeders, if any.
    Run php artisan serve