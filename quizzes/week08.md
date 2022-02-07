# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The package.json file holds metadata relevant to the project and is used to give information to npm that allows it to identify the project as well as handle the project's dependencies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
The package.json needs to be deployed in the top level to ensure that all necessary modules are imported to the grander application.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
Npm i for installing necessary node modules/packages.
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Env files
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
With with the Heroku command line, the dashboard, your logging add-on, or in your log drain.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
From the heroku command line you will run a git remote command for the GitHub repository and a git push to the heroku master branch.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Having multiple development branches will prevent merge conflicts and allow for the team to 'code small' before pushing changes to the master that could potentially break the application.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code review should happen after necessary testing and before pushing it to the main branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Git merge
```