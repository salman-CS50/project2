# Git Basic commands
This project was created from local system.

To initialize a .git file to track changes:
    git init(Add a new .git file to the current working directory)


To create a new repo:
    -> manually create a new repository in the github
    -> git remote add origin <link> (Give remote repository link to add the repository to the local repository)
    -> git remote -v (To verify the remote)
    -> git branch (To check the branch)
    -> git branch -M main (To rename a branch)
    -> git push origin main (To add a new content to the git)

To make the origin main as the default route/path:
    -> git push -u origin main
        Now you can use only the git push

To combine two commands as a single one:
    git commit -am "<message>"
        Here you are adding the file to the staging area and commit the file at the same time
        -a : To add file to the staging area
        m : To commit the file
