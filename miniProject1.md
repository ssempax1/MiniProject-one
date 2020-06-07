# Project 1

## Usage of Git, Docker, Automated Testing, and Continuous Integration


---

## GitFlow:

### Typical workflow when using Git workflow is:

1. git pull (or  git fetch)

2. As many times as you desire (but try to limit it  few times):

    * Make local edits on your branch
    * Examine the local edits: git status and git diff 
    * git commit -m "comments"
    * git pull if local master is updated 
    * git push origin master

3. git pull master remote

4. git push to master remote

---

## Terms:

1. **Repository:**  A basic element of GitHub that contains all project files and documentation, and also stores each file’s revision history. It can be labeled as public or private and can have multiple collaborators.

2. **Clone:** A  copy of a repository that is stored locally on a user’s computer. It is also defined as the act of making the copy.

3. **Fork:** A personal copy of another user’s repository that is stored on one’s account. It allows a user to make changes to the project without affecting the original repository/project.

4. **Branch:** A parallel version of a repository that is contained with the repo but does not affect the primary or master branch. This allows developers to work freely without disrupting the master (or main) version.

5. **Commit:** An individual change to a file or a set of files. When a commit is made, a unique ID is created to keep record of the changes committed as well as who made them and when it was created. They usually contain a brief description of what changes were made as the commit message.

6. **Merge:** To take the change from one branch (or fork) of a repository and apply them to another. A merge can also be done through a pull request.

7. **Checkout:** To change a user's current working branch to another branch. This can also be used to create a new branch.

8. **Push:** To send committed changes to a remote repository on GitHub so that others may access and view the changes.

9. **Pull:** To fetch and merge changes into current branch.

10. **Remote Add / Remove / Show:**
    - Remote add: To add a new remote to the repository
    - Remote remove: To remove a remote. All remote-tracking branches for the remote are removed
    - Remote show: To provide information about the remote

11. **Status:** A visual representation within a pull request that shows whether the developer’s commits meets the conditions set for the repository they are contributing to.

12. **Master Branch:** The default development branch automatically created when a git repository is created.

---

*View changelog [here](P1_CHANGELOG.md)*
