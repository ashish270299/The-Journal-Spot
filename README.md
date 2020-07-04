# The-Journal-Spot
An e-journal website where you can record your daily stuff from anywhere and anytime.


The code of the website is in the repo. But we need to clone via HerokuCLI as it is deployed there.
Website Link : https://thejournalspot.herokuapp.com/


Steps to perform Heroku cloning::

1).  Install the Heroku CLI
     Download and install the Heroku CLI.
     If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.

2).

    $ heroku login
    Clone the repository
    Use Git to clone thejournalspot's source code to your local machine.


3). 

     $ heroku git:clone -a thejournalspot
     $ cd thejournalspot
     Deploy your changes
    
4). Make some changes to the code you just cloned and deploy them to Heroku using Git.

    $ git add .
    $ git commit -am "make it better"
    $ git push heroku master
