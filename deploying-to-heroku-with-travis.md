# Heroku Deployment
This tutorial is heavily based on the documentation provided by Travis found at https://docs.travis-ci.com/user/deployment/heroku/

## Video
I made this video with Ryan K. It came out alright but the audio is pretty bad and not everyone is a visual learner so I wrote this guide as well.
<a href="http://www.youtube.com/watch?feature=player_embedded&v=SJY_kbk-YcA" target="_blank"><img src="http://img.youtube.com/vi/SJY_kbk-YcA/0.jpg" 
alt="Travis and Heroku Tutorial" width="240" height="180" border="10" /></a>

## Definitions
* Travis CI or Travis Continous Integration - Wouldn't it be nice if a computer tracked your project and yelled at you the second you broke any of your tests? This tutorial assumes that you'd say yes.
* Ruby - A programming language, we'll be using its package manager, gem, to install Travis CLI
* Travis CLI or Travis Command Line Interface - Allows you to run travis commands from CMD or Git Bash, super useful and installing it will save you a lot of time later. I think it's programmed in Ruby.
* Heroku CLI or Heroku Command Line Interface - Similar to Travis CLI but can be installed right out of the gate. For our purposes we're using this just to get your api key so very small but like Travis CLI, it'll save you a lot of time later. You do need to login to it just like you have to login to Git Bash.
* Heroku - Web hosting/database service. First tier is free, second tier is cheap ($7 per project per month), the rest of the tiers start getting expensive but we won't need them. In fact you should really only need the Free tier except for when you're presenting your final project. They also prorate you to the second so you wouldn't pay for the full $7 if you ran their Hobby Tier for less than a month.

## Make a Travis CI account
https://travis-ci.org/
Sign in through GitHub.

## Make a Heroku CI account
https://dashboard.heroku.com/

## Ruby
In order to install the Travis Command Line Interface (CLI) we're going to have to first install Ruby: https://rubyinstaller.org/
After you complete the install wizard you may be prompted to enter a number 1, 2, or 3. Just enter 1 and close out of the window when it says it's done installing.

## Travis CLI
After Ruby is done installing restart Git Bash, then run one of two commands. I used the first one, which is the production version of Travis CLI. You could also use the second which is the development version and since we are developers maybe this is the better choice.
1. `gem install travis -v 1.8.8 --no-rdoc --no-ri`
OR
1. `gem install travis --pre`

## Heroku CLI
https://devcenter.heroku.com/articles/heroku-cli
Pretty easy to install from what I remember. Select the installer for your machine. Once this is finished installing open up Command Prompt (that thing that looks like Git Bash but with less colors and comes with Windows, you can find it by searching). Enter the following:
`heroku login`
You should then be prompted for your email and password for Heroku. Once you've entered it restart Git Bash again.

## Create Heroku app

## Configure .travis.yml