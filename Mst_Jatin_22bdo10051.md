1.  Run the status command. Notice how it tells you what branch you are in.
2.  Create branch using **git branch** command
3.  Now checkout to the branch using **git checkout <branch_name>**
4.  Edit the files in it and add make a couple of commits using **git commit**
5.  Now using **git log** check the commit history of the branch created
6.  Now switch back to the main branch and check the status using **git status**
7.  Also check the commit history of main branch using git log and see there is no commits made in main branch
8.  Now switch back to the branch using checkout and make chenges in the files previously created but do not make the changes in the main branch.
9.  Now checkout to main branch and using **git merge <branch_name>** name merge the changes of feature branch into main
10.  Now check DAG using **gitk** command
11.  Switch back to your branch. Make a couple more commits.
12. Switch back to master. Make a commit there, which should edit a different file from the ones you touched in your branch – to be sure there is no conflict.
13. Now merge the branch again.
14. Look at git log again to see the commit history.
