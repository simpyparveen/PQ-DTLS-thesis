# PQ-DTLS-thesis

Using Git


Cloning: When we clone a repository, all the files are downloaded to the local machine but the remote git repository remains unchanged. 
Clones a repository into a newly created directory, creates remote-tracking branches for each branch in the cloned repository (visible using git branch --remotes), and creates and checks out an initial branch that is forked from the cloned repository’s currently active branch.

Fork : While there are other ways to take a copy of the repository and work with it, forking is the preferred method, because it makes it easier to submit pull requests (which notify the original owner that you have changes that you'd like considered for inclusion) later.

Pull & Push request : A "pull request" is you requesting the target repository to please grab your changes. A "push request" would be the target repository requesting you to push your changes. When you send a pull request, you're asking (requesting) the official repo owner to pull some changes from your own repo.
Pushing sends your changes up to GitHub, so they can be shared with the rest of the world. It also serves as a hedge against data loss.
Pulling is the opposite of pushing--it retrieves changes from the remote location and applies them to your local repository. 


Commit - committing is the process which records changes in the repository. Think of it as a snapshot of the current status of the project. Commits are done locally.





$ git init

$ git add .  

  #Changes to be committed: (use "git rm --cached <file>..." to unstage)

$ git commit -m "First commit"

$ git push origin your-branch
  Eg : git push origin master  https://github.com/simpyparveen/PQ-DTLS-thesis.git

$ git status




References:
https://help.github.com/en/github/managing-files-in-a-repository/adding-a-file-to-a-repository-using-the-command-line
https://gist.github.com/alexpchin/102854243cd066f8b88e
https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line
