CIS 191 Project 3
-----------------

This is a demo site that is a simplified version of the CIS 191 website. It is
used as a testbed/training ground for Git usage and merge conflict resolution.

A git hook is a script that is either executed before or after the either commit
or a push to some remote. In our case, the post-receive hook in www of our EC2 account,
the script is run after the commits are pushed to the remote named cloud. 

The python server (in particular the server.py file) opens a hidden file named .cis191pj3.pid
which it then publishes online.

A bare repo in git is a new repo that just contains the version control files with no
work tree (working files). It doesn't contain the .git directory, but instead contains
all the contents of the .git directory in the main directory itself. You do not have 
pass in a url or ssh to a remote repo while making a bare repo.
