# Q&A
---
## Error:src refspec mater does not match any
* Make sure that your local repository is not empty so that you have something to commit.

---
## Error:failed to push some refs to 'git...
* It happens sometimes when you want to push the local repository to the remote master branch.
* Usually because the github create the repository along a `README.md` file but it is not in the local one.
* **[common]** git pull --rebase origin master
	* pull = fetch + merge
* **[common]** git push -u origin master