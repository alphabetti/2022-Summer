## Getting Started
1. Install and Register for GitHub
2. Install PyCharm
3. Get this _Notebook_ and open it in your pycharm
4. Start to Code!

### Registering for GitHub and installing Git
(GitHub)[http://www.github.com] is a place where developers store code and discuss stuff.  Storing it in places like this means you don't lose it when your computer dies, and you can regularly save your changes in a way you can rewind, and also get advice from other people, as well as share cool stuff with other people.

We're not really going to be doing much with GitHub just yet, but it's a good idea to get an account on there.

* Go to (GitHub)[http://www.github.com] and set up an account
* You should also install git on your machine.  Git is the version control software used for that cool rewind stuff I mentioned earlier.  There are instructions (here)[https://github.com/git-guides/install-git]

### Installing PyCharm
Code is generally just written in text, and stuff (an interpreter, a compiler) runs that code to make it useful.  However, there are really powereful Integrated Development Environments (IDE)s out there which will make it a lot easier to write code, provide suggestions, allow easy editing of code and so on.  We're going to be working with python for this project, and PyCharm is one of the best IDEs for it.  It's produced by a company called JetBrains and a lot of commercial companies buy this product.  However - great news you don't have to buy it, you get it free as a student, you just need to sign up with your bms email address.

(Install PyCharm)[https://www.jetbrains.com/pycharm/] setting up a new account with your bms email.

### Installing this Repository onto your machine
* Let Daki know your GitHub account name and I'll permission you access to this repository (think of it as an area where all code for one project, in this case the 2022-Summer coding exercises are stored).  You can then install it locally.

* Navigate to the repository area at [Daki's GitHub](https://github.com/alphabetti/2022-Summer)
* Click on the button at the top right labelled 'fork' and click on `Create Fork`.  This will make a copy of the repository in your own GitHub.  Changes to this repository are now detached from the original repository (though you can propose that they get merged back in!)
* Once you've created the fork, you can download it to your machine. _You'll likely need to grab Daki for this bit'_
* Click on the big green 'Code' button at the top right of your forked repo in GitHub, and click on the copy icon next to what looks like a web address
* Make a new folder on your machine called 'Code'
* Open a shell and navigate to that folder (if the folder is open in explorer you can type in 'cmd' in the top bar of that folder to do this)
* in the shell window type in `git clone ` then paste in the web address from above
* GitHub will pull the code in locally, and it will now be available on your machine.
* Open up PyCharm, and point to the directory you've just made.

### Installing Jupyter
* Ths learn python file is what is called a _Jupyter Notebook_, you need to install a tool called Jupyter to be able to use these.  (Follow the Instructions At)[https://blog.finxter.com/how-to-install-jupyter-notebook-on-pycharm/]

### Next Steps
> Before doing anything else run through the learn_python.ipynb file to give yourself a primer on python functionality.  Then there's a load of options from here.  If that looks dull you can always try to learn just be working through the games folder.

* Games on computers are fun yeah?  
    * If you'd like to write some simple games to play against the computer look in the _games_ folder
    * If you'd like to write an interactive game with graphics look in the _pygame_ directory
* Fractal's are never ending patterns that show more and more detail as you focus deeper on them.  To explore some fractal imagery have a look in the _fractals_ directory
* Computers can be used to play some cool music - look in the _music_ folder
* There's an amazing amount of data available on the internet, to explore what kind of information you can find out go to the _apis_ directory
     - Generate a random person's profile
     - Generate AI Art
     - Mummy's gaming data
* Some mathematical challenges to try can be found in the _maths_ folder
    - Generating Random Numbers
    - Normal distributions off random data
* A lot of programmers like writing code as efficiently as possible.  If you'd like to try some of these challenges, look in the _leetcode_ directory

### Debugging Code
To spot errors first flick to the "Problems" tab, PyCharm will highlight anything which is bad python, just double click to go to the line and you can go fix it

### Saving your code

Do remember to save your code reasonably often.  When you're finishing up, navigate to the terminal in PyCharm, and type in

> git add .

_This adds all your outstanding changes to what you're going to be saving to the cloud_

> git commit -m "Say what you did in this block of changes as an example"
> git commit -m "I started writing Rock Paper Scissors"

_This associates the code changes with a specific 'commit' which means they were all made in one larger change_

> git push

_This pushes the changes to the source control area._
