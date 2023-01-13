<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS2DVc8OpBLjgghQJjcK5-WbOT8Bo3lgkye-A&usqp=CAU">

This will be the main lecture repository for the Flatiron School Data Science Cohort 010923. Welcome to the cohort!  Many lectures we deliver here have notebooks associated with them to demonstrate code and have excersizes for you to do as the lectures go on. To work along with your instructor, you'll need to get your own versions of those notebooks, and you'll do that through this repo. 

# Instructions to Connect to This Repository:

## These steps you should only need to do at set up:

**1) FORK this repository, creating copy on your own GitHub account**

* In order to fork, look to the upper right of this page, between 'Watch' and 'Star'. From that drop down you should see an option to create a new fork.

* That will open a new page, and you'll be given an option to select a new owner for the fork. Select your own account. Ignore the other options.

**2) CLONE your fork to your local computer**

* To do this, navigate in your terminal to an appropriate folder. We recommend you have an overall 'Flatiron' folder either in your documents or on your desktop.
* Once you're in the right place, you'll need to input the following command, replacing '[yourusername]' with your Github account:

<code>git clone https://github.com/[yourusername]/DS-NATL-010923.git;
</code>

* Make sure NOT to clone this repo into a folder that is already a Git repo. 

**3) Add the /flatiron-school/ version as the upstream (to pull future changes)**

* **Navigate into the new folder** you created when you cloned down the fork, and then input this code:

<code>git remote add upstream https://github.com/flatiron-school/DS-NATL-010923.git</code>

## These are the steps you need to do to get updated notebooks:

**1) Grab the changes from the upstream repo**

* Using the terminal from inside the appropriate folder, input this command:

<code>git fetch upstream</code>

**2) Merge new changes onto your local repo**

<code>git merge upstream/main -m "meaningful message about what you're updating"</code>

## And that's it! You should be set to go.

If you want to push your changes from your local to the forked version of the repo use these steps:

<code>git add [filename]</code>

<code>git commit -m 'message here'</code>

<code>git push</code>


#### What did we just do?

Git is a very popular tool for version control and collaboration in coding and development. Github is a website that hosts git repos (short for repositories) online. There are many ways that repos can be set up to relate to each other, but because we want you all to be able to keep your own versions of your notes in these lecture notebooks, we had you all create seperate FORKS so that your work won't overlap and cause conflicts with another student's work. A FORK in Git creates a seperate entity so that changes in one FORK won't affect the others.  

When you use the <code>CLONE</code> command in the terminal Git creates a folder on your local computer it automatically creates a connection between the repo stored in Github and the folder in your local machine. Git will try to treat the version on your local and the version on Github as basically part of one entity, and it'll want to keep things harmonized between your local and the cloud version, and will throw errors if they diverge and you try to bring them in line. This is unlike a FORK, which by default breaks the connection at the point at which you created the FORK. 

But! We want you all to be able to access new lectures as they go up in the original version of the repository. In order to do that we had you set the Flation repo as the UPSTREAM repo for your FORK. This creates a relationship sort of like this:

![gitrelationshipimage](https://user-images.githubusercontent.com/85522002/210625512-7f91212f-217d-4005-a856-51dc3bc9b183.png)

When you FETCH from the UPSTREAM that will stage the changes in your local repo as a new branch. When you MERGE that new branch in it will finalize those changes and bring the new notebooks into your main branch on the local version. You can think of a BRANCH as small, temporary fork, or of a FORK like a bigger, permanent, BRANCH. This is not a perfect analogy, but it's pretty close.
