# Presentation Walkthrough


## Part 1: Demo: Showing the problem
1. Bring up terminal.

1. First we need to know what Python interpreter are we using?

        $ which python

1. We will see output like the following.

        /usr/local/bin/python

1. Lets check out what packages are in there.

        cd /usr/local/bin
        ls

1. Our Python packages are stored in a slightly different directory though.

        cd /usr/local/lib/site-packages/

1. We are working on Django 1.6 for our day job. We still have not had time
   to upgrade to the latest release with all the new functionality that is
   being built. South is being used with the project to handle schema 
   migrations:

        sudo pip install django==1.6.10 South

