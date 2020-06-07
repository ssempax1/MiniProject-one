# Project 1

## Usage of Git, Docker, Automated Testing, and Continuous Integration

There are many components in the software development industry that helps build software in a fast manner to increase productivity. Of all major components, they include using Git, Docker, automated testing, and continuous integration.

Git is a very commonly used VCS (Version Control System) that allows users to track changes made to their files while maintaining a history of what have been done. If an error is ever made, users are allowed to go back to specific versions of the file before the error was made. Git makes collaboration much easier by merging the changes make by all users into one branch or source. This ensure that Git is very useful regardless if the user is working as part of a team or individually.

Docker is a tool that uses containers to make it simpler to create, deploy and run applications. It allows developers to build and test their code in any environment to be able to catch bugs early in the application development cycle. By using Docker, it helps streamline the process of development, save time on the builds and allow developers to run tests in parallel. Docker can integrate with version control systems like GitHub as well as Integration tools to create an image that can be added to the Docker registry. This would handle the inconsistencies between the different types of environment.

Automated testing the best way for developers to increase the effectiveness, efficiency and coverage of their software testing. With manual testing, test engineers strive to catch all defects before the product is released yet they often reappear, even when following the best manual testing processes. An automated testing tool is able to playback pre-recorded actions, check whether the results match the expected behavior and then report the success of failure of the test to the test engineer. Automated testing can be extended to perform tasks that are not possible with manual testing.

Continuous Integration (or CI) is a development practice that requires developers to integrate code into the share repository several times a day. With CI, errors can be detected and located early and easily. Since there is frequent integration occurring, there is less back-tracking needed to discover where something went wrong and developer are allowed to focus more on building the features of the product. Continuous Integration is very cheap compared to not integrating continuously in development.

These features are considered as essential components of successful development projects. The results from helping build software in a secure and fast manner increases the productivity and competitiveness of a company.

---

## GitFlow:

### Typical workflow when using GitFlow is:

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
