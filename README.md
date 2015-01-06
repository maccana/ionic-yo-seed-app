ionic-yo-seed-app
=================
Setup
Pre-requesites:
Install NodeJS, Git, Ruby,Compass

If you are using npm 1.2.10 or above, this will also automatically install grunt and bower for you. If you’re on an older version of npm, you will need to install them manually:

  npm install -g grunt-cli bower
Yeoman
    npm install -g yo
Ionic Generator
    npm install -g generator-ionic
Creating the project
Make a new directory, and cd into it

    mkdir my-ionic-project && cd $_
Run yo ionic

    yo ionic
The generator will ask several question to setup the project for us

[?] Would you like to use Sass with Compass (requires Ruby)? (y/N)
[?] Which Cordova plugins would you like to include? (Press <space> to select)
[?] Which starter app template which you like to use? (Use arrow keys)
The last step gives you a basic app already setup in a given way using tabs, or a side menu. Choose any, these are just to help you start and avoid writter’s blank page fear. :)

Once we have answered these questions, the generator will perform all steps creating folder structure, downloading all node and bower dependencies, setting up grunt to build, serve and everything you might need to develop a web application.

Once yeoman completes its work, run the following:

    grunt serve
