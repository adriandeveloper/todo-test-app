Front-End Testing of a Node App
=============
### Overview

A MEAN Todo App Integrated with End-to-End Automated Test

The MEAN Todo App was cloned from https://github.com/arvindr21/MEAN-Todo-App 
and integrated with automated test using [nightwatchjs](http://nightwatchjs.org/). 
This project also utilizes [qualitywatcher](https://github.com/QualityWorksCG/qualitywatcher) 
so the test results can be viewed on the [qualitywatcher.io](http://qualitywatcher.io/) dashboard.

### Install & Run Application

* Download/Clone the repo
* Run `npm install`
* Run `npm run gulp` and navigate to `http://localhost:3000` to view the app

_*Ensure Mongodb is running and JAVA is installed*_

### Automation

* Run Test
    * `npm test`
* Run Test and see reports on [qualitywatcher.io](http://qualitywatcher.io/) dashboard
    * See [qualitywatcher](https://github.com/QualityWorksCG/qualitywatcher) node mdoule for setup