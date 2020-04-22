learning git command

first using git remote add NEW url to add a remote repo to your machine. its name is NEW.
you can rename it to other later by using command:
git remote rename NEW origin

This will rename NEW to 'origin'

After that, you can add another remote repo

Now, let's start to fetch 

git fetch origin
after this we can create a branch to start our modification safely

git checkout -b changes origin/master


