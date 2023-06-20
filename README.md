# Unit tests and email notification CI/CD

CI/CD pipeline implemented using GitHub Actions on a clone of one of my projects.

Upon a commit or pull request on the main branch:

* A Python virtual environment is created with version 3.8
* Dependencies stated in requirements.txt are installed
* Unit and functional tests specified in <code>./test</code> folder are executed.
* An email is sent to project owner on the build status of the action. A failure to build will mean some/all parts of unittest has failed. Refer to logs in actions for details
