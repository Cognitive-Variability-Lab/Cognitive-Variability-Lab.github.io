# cogvarlab.github.io

Welcome to the source code for the website of the Cognitive Variability Lab at ENS Paris.

## Steps to install a local copy of this website (e.g. for testing):

* Clone a copy of this repo:
    
    git clone https://github.com/Cognitive-Variability-Lab/Cognitive-Variability-Lab.github.io

* cd into the repo.

* Install Jekyll:

    gem install bundler jekyll

* Start an instance of the website (change or increment the port number if needed):

    jekyll serve --port 4000 --watch --baseurl=""

* Go to this address in a browser (change or increment the port number if needed):

    localhost:4000

* When you are finished, you should kill the process with ctrl + c.

* Extra tips: 

    jekyll clean # cleanup your local repo including historical stuff
    jekyll build # rebuild the site

* How to push your new changes to the github repo:

    git add .
    git commit -m "Updated site"
    git push origin main

## Credits

This website was designed by Sakib Hossain of the Keedy Lab.
The basic framework for this website was borrowed from the website of the Fraser Lab at UCSF (www.fraserlab.com).
Yinan Cao adapted the original repo to create this site for the cvlab.
This website uses CSS styles from https://templated.co.
