# Start Up
---
## Install & initialization
* Install
	* **[Ubuntu]** sudo apt-get install git
	* **[windows]** download git-bash and install
* Initialization
	* **[common]** git config --global user.name "your name"
	* **[common]** git config --global user.email "email@exaple.com"

---
## Create a Repository
* **cut** to the **path** where you want your repository to be created
* **[common]** git init
	* to trans the directory into a repository
* remember that you can have not only one repository on your PC,which means you have to operate the repository you want **under exact its own path**
---
## Link to a Remote Repository
* **[common]** git remote add origin git@github.com:Qsirman/Git.git
	* the **Qsirman/Git.git** part can be replaced by your repository's address
* **[common]** git push -u origin master
	* One thing you have to mind is that you must add & commit something to your local repository,which means you **can not push a blank repository to remote origin**
