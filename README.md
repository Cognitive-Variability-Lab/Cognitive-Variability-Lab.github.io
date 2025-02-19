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

* Too complicated?!

To simplify the process of cleaning, building, committing, and pushing your Jekyll site, you can create a custom alias command. This alias will execute multiple tasks in one go.

### Setting Up the Alias

Follow these steps to set up the `deploy` alias:

1. **Open your terminal.**

2. **Edit your shell configuration file:**

   - For **zsh** (the default shell in recent macOS versions), run:
     ```bash
     nano ~/.zshrc
     ```

   - For **bash**, run:
     ```bash
     nano ~/.bash_profile
     ```

3. **Add the alias command:**

   Scroll to the bottom of the file and add the following line:
   ```bash
   alias labsite-deploy='jekyll clean && jekyll build && git add . && git commit -m "Updated site" && git push origin main'

4. Save the file:

    If you're using nano, press CTRL + X, then Y to save, and Enter to confirm.

5. Reload your shell configuration file:

    To apply the changes, run one of the following commands:

    For zsh:
     ```bash
     source ~/.zshrc
     ```

    For bash:
     ```bash
     source ~/.bash_profile
     ```
     
6. Use the alias command:

    You can now use the deploy alias to automatically clean, build, commit, and push your site with a single command:

    ```bash
    labsite-deploy
    ```

## Credits

This website uses Jekyll and was designed by Sakib Hossain (Keedy Lab: https://keedylab.org/) using a framework adapted from the Fraser Lab (UCSF: www.fraserlab.com). 
Yinan Cao modified the original repo for the cvlab. CSS styles are from https://templated.co.
