#Git Commands

In this file, you can fin some of the most important commands or cheats that exists in git.

##Configuration

Obviously, we need to set up our environment in which we are going to work. For this, git provides us some cheats to set default values. For example:

`$ git config --global user.name "Your name"` 
This set us the name that will be attached tp our commits and tags.

`$ git config --global user.email "Your email"`
It is like the previous one, just that is our email, not our name (It shows in commits and tags).

## Start

Then, we have to start our project, for this, git gives us these tools:

`$ git init [project name]`
This will create a local repository inside of a directory created locally as well.

`$ git clone [project url]`
This comman will download a project from a remote repository.

## Daily Flux

Once we started our project, we will get into it and it is important to know how to work properly using git commands.

`$ git status`
This is probably the command that we will use most when we are working, because, this command displays the status of thw working directory, showing us created, deleted or modified files

`$ git add [file]`
This command will be used for staging your files, ready to commit them.

`$ git diff [file]`
It shows changes between our working directory and the staging area.

`$ git diff --staged [file]`
It shows changes between the staging area and the local repository.

`$ git reset [file]`
This cheat will make our repository return to a previous known state.

`$ git commit`
Creates a new commit of the changes that are in the staging area. The commit should have a message, you can add one directly just typing `-m "Your message"` just after the command from above.

`$ git rm [file]`
Probably, sometimes you will need to undo things or to add something to your staging area and this command would be helpful for some of this cases, will remove the file from the working directory and staging area.

`$ git stash`
I think this cheat was not seen in class, but in my experience as a git user, I think is very useful, it saves the current changes of the working directory into a stash so we can use them later.

`$ git stash pop`
Applies the stored changes in the stash into the working directory again.


## Branching

While we are working in a team, surely, we are going to need the use of branches, so we can modify our project or work, without affecting in other changes or features, for this, git provides us this commands.

`$ git branch [-a]`
Shows a listing of all local branches.

`$ git checkout [-b][branch_name]`
Switches our working directory to the specified branch, the [-b] creates a new branch if it does not exist

`$ git merge [from name]`
It merges or joins two branches, the [from name] to the current branch.

`$ git branch -d [name]`
When we merge a branch to another, the branch that has been merged, is now "useless", so we can remove thibranch if is already merged in any other.
