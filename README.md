# Unit tests and email notification CI/CD

CI/CD pipeline implemented using GitHub Actions:

* Virtual environment is created with the specified version
* Dependencies in requirements.txt are installed
* Unit and functional tests specified in <code>./test</code> folder are executed with the <code>flask test</code> command as if it were done locally
* An email is sent to me on the build status of the action.
