# cogvarlab.github.io

Here you can find the source code for the website of Cognitive Variability Lab at ENS Paris.

## Steps to install a local copy of this website (e.g. for testing):

* Clone a copy of this repo:
    
    `git clone https://github.com/Cognitive-Variability-Lab/Cognitive-Variability-Lab.github.io`

* cd into the repo.

* Install Jekyll:

    `gem install bundler jekyll`

* Start an instance of the website (change or increment the port number if needed):

    `jekyll serve --port 4000 --watch --baseurl=""`

* Go to this address in a browser (change or increment the port number if needed):

    `localhost:4000`

* When you are finished, you can kill the process with `ctrl + c`.

* Extra tips: 

    `jekyll clean` # cleanup your local repo including historical stuff
    
    `jekyll build` # rebuild the site

* How to push your new changes to the github repo:

    `git add .`

    `git commit -m "Updated site"`

    `git push origin main`

## Credits

This website uses Jekyll and was designed by Sakib Hossain (Keedy Lab: https://keedylab.org/) using a framework adapted from the Fraser Lab (UCSF: www.fraserlab.com). 
Yinan Cao modified the original repo for the cvlab. CSS styles are from https://templated.co.
