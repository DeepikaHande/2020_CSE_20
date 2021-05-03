# Virtual-3D-Trial-Room

## Team Members

1KS17CS010 - Anusha A G  
1KS17CS022 - Deepika S H  
1KS17CS023 - Divya Yashaswi Kanney  
1KS17CS027 - H Priyanka

### Git Setup steps

- Download git for your OS  
  [Git Website](https://git-scm.com/downloads)  
  [Installation Guide](https://www.youtube.com/watch?v=nbFwejIsHlY)
- Fork deepika's repository
- Clone your forked repository into your workspace using SSH or HTTPS

```bash
$ git clone <your-repository-git-link>
```

- Navigate to your local git repository and create a new branch using

```bash
$ git checkout -b <branch-name>
```

- Make sure you're on your branch. Go ahead and make necessary changes.
- Stage your changes

```bash
$ git status                    # Check your staging status
$ git add <file-name>           # To stage a specific file
$ git add .                     # To stage all your changes
```

- Commit your changes using

```bash
$ git commit -m "your-commit-message"
$ git commit -m -a "your-commit-message"      # To directly committing all your changes without staging
```

- Push your changes to GitHub

```bash
$ git push -u origin <branch-name>                # To push your changes on a newly created branch
$ git push --set-upstream origin <branch-name>    # Alternative for the above command
$ git push                                        # To push your changes on a usual basis
```

- Pull your changes from GitHub  
  **Note: Make sure you pull all the new changes from Deepika's repository before push your own changes**

```bash
$ git remote add upstream <deepika-repository-git-link>       # Link deepika's repository with yours (to be done only once)
$ git remote -v                                               # Verify your remote status
$ git checkout main                                           # Switch to your main branch
$ git fetch upstream                                          # Pull changes from deepika's repository
$ git merge upstream/main                                     # Merge your main branch with deepika's for the changes to download

$ git stash                                                   # use this command to get rid of your changes in case you forgot to pull first
$ git pop                                                     # use this command to bring back your changes after performing the pull operations

$ git pull                                                    # usual command to pull changes from one branch to another within your own repository
```

- Done with the branch? Delete it.

```bash
$ git branch -d <branch-name>
```
