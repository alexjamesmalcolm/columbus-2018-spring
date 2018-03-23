# Heroku Deployment
This tutorial is heavily based on the documentation provided by Travis found at https://docs.travis-ci.com/user/deployment/heroku/

# Definitions
Travis CI or Travis Continous Integration - Wouldn't it be nice if a computer tracked your project and yelled at you the second you broke any of your tests? This tutorial assumes that you'd say yes.
Ruby - A programming language, we'll be using its package manager, gem, to install Travis CLI
Travis CLI or Travis Command Line Interface - Allows you to run travis commands from CMD or Git Bash, super useful and installing it will save you a lot of time later. I think it's programmed in Ruby.
Heroku CLI or Heroku Command Line Interface - Similar to Travis CLI but can be installed right out of the gate. You do need to login to it just like you have to login to Git Bash.

# Ruby
In order to install the Travis Command Line Interface (CLI) we're going to have to first install Ruby: https://rubyinstaller.org/
After you complete the install wizard you may be prompted to enter a number 1, 2, or 3. Just enter 1 and close out of the window when it says it's done installing.

# Travis CLI
After Ruby is done installing restart Git Bash, then run "gem install travis -v 1.8.8 --no-rdoc --no-ri" in Git Bash with no quotes. Alternatively you can run "gem install travis --pre", this is the development version and since we are developers maybe this is the better choice, not the one I picked though so the choice is yours.

# Heroku CLI
https://devcenter.heroku.com/articles/heroku-cli
Pretty easy to install from what I remember. Select the installer for your machine.