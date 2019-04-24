# Uniqueness 

## Distributed
Every developer has his own repository. His repository would be used to put in files and take out the files from the repo.

and If he wants to share his code with others he can do that as well, **without disturbing others work**

## Contents Verified using SHA1 algorithm.
Everytime Git Commits your file it uses the file content and generates a Hash for it and stores that hash as well.

And everytime you take out the file from the repository it takes the content and verifies with the hash with the one it stored and if it finds they are not same then it reports.

This makes it very robost if your remote repo is hacked by someone, You will get to know about that.

## Tracks complete list of files in a project as one content than individuals.

Aside from the practical distinctions between SVN and Git, their underlying implementation also follow entirely divergent design philosophies. Whereas SVN tracks differences of a file, Git’s version control model is based on snapshots. For example, an SVN commit consists of a diff compared to the original file added to the repository. Git, on the other hand, records the entire contents of each file in every commit.

## Lightweight Branching & Easy Merging ( ~ 5 merges can be done in a day).
![branching](img/branches@2x.png)

Git allows and encourages you to have multiple local branches that can be entirely independent of each other. The creation, merging, and deletion of those lines of development takes seconds.

This means that you can do things like:

** Frictionless Context Switching**. Create a branch to try out an idea, commit a few times, switch back to where you branched from, apply a patch, switch back to where you are experimenting, and merge it in.

**Role-Based Codelines.** Have a branch that always contains only what goes to production, another that you merge work into for testing, and several smaller ones for day to day work.

**Feature Based Workflow.** Create new branches for each new feature you're working on so you can seamlessly switch back and forth between them, then delete each branch when that feature gets merged into your main line.

**Disposable Experimentation.** Create a branch to experiment in, realize it's not going to work, and just delete it - abandoning the work—with nobody else ever seeing it (even if you've pushed other branches in the meantime).


