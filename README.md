<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS2DVc8OpBLjgghQJjcK5-WbOT8Bo3lgkye-A&usqp=CAU">


# Written Instructions to Connect to This Repository:

Welcome to the cohort!

## These steps you should only need to do once:

1) FORK this repository, creating copy on your own GitHub account

2) Then clone your fork down to your local computer

<code>git clone https://github.com/[yourusername]/DS-NATL-010923.git;
</code>


3) Add the /flatiron-school/ version as the upstream (to pull future changes)

<code>git remote add upstream https://github.com/flatiron-school/DS-NATL-010923.git</code>


4) You can make changes to the notebooks now! Remember to push your changes to your forked version of the repo (to put your local changes up online):

<code>git add [filename]</code>

<code>git commit -m 'message here'</code>

<code>git push</code>

## These are the steps you need to repeat whenever you want to get updated notes:

5) Grab the changes from the upstream repo

<code>git fetch upstream</code>

6) Merge new changes onto your local repo

<code>git merge upstream/main -m "meaningful message about what you're updating"</code>
