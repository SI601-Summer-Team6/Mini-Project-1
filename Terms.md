# Definition of the Terminology
* **Repository:** a stored project on Github.
* **Clone:** using links(SSH or HTTPS) to download the repository to the local computer, tagging the private and public key.
  * **Example:** git clone git@github.com:SI601-Summer-Team6/Mini-Project-1.git
* **Fork:** sharing the authority of editing the repository with the others worthy trust.
* **Branch:** could be like a back up file on the Github for develop.
  * **Example:** git checkout -b newbranch
* **Commit:** As a verb could be like saving for a file. As a noun could be like a updated file. 
  * **Example:** git commit -m'Example message'
* **Merge:** used to conbine the perivous version coding with the other one.
  * **Example:** git merge Terms
* **Checkout:** could be interpreted as a selectiing command. To inform the machine which commit I would like to work on.
  * **Example:** git checkout Terms
                git merge master
* **Push:** uploading the commits on the local to the remote.
  * **Example:** git push
* **Pull:** according to the git tutorial "git pull = git fetch + git merge." Which is not only downloading the latest version on the                    remote but also merge that version with the local version.
  * **Example:** git pull
* **Remote Add:** using "git remote add" to connect a new remote repository also name the new remote repository.
  * **Example:**
  git remote -v *(this command is requesting a list of all the remote repositories that are currently connected to the local repository, for the user to confirm the remote reopsitory is the new one for the local device.)*
  git remote add Miniproject2 https://github.com/SI601-Summer-Team6/Mini-Project-1.git
* **Remote Remove:** using "git remote remove" is to disconnect the remote from the local repository.
  * **Example:** git remote remove Miniproject2
* **Remote Show:** It lists  not only the URL for the remote repository but also the tracking branch information. It tells users that which branch they are working on; Would run git push merged and so on helpful information.
  * **Example:** git remote show origin
* **Status:** to Show the working tree status.
  * **Example：** git status
* **Master Branch:** the main branch for the repository.

![perfect example image](https://v.spirit.codes/images/2019/03/30/git.png)

Reference:(https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes)
