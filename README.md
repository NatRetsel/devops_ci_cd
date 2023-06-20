# Unit tests and email notification CI/CD

CI/CD pipeline implemented using GitHub Actions:

* Virtual environment is created with the specified version
* Dependencies in requirements.txt are installed
* Unit and functional tests specified in <code>./test</code> folder are executed.
* An email is sent to me on the build status of the action. A failure to build will mean some/all parts of unittest has failed. Refer to logs in actions for details
