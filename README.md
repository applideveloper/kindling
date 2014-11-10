[![Build Status](https://travis-ci.org/tylerdmace/kindling.svg)](https://travis-ci.org/tylerdmace/kindling)
[![Dependencies Status](https://david-dm.org/tylerdmace/kindling.png)](https://david-dm.org/tylerdmace/kindling)
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/tylerdmace/kindling?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

kindling is a less sucky version of Tinder. It's not ground-breaking nor innovative in any measurable way -- it's simply less sucky.

# About
###Technical details
I am developing kindling on the MEAN stack. A full list of tools used:
* MongoDB
* Angular
* Node, Express
* Protractor (w/ Selenium), Karma, and Jasmin
* Grunt
* Bootstrap, Sass, Font Awesome, and Material Design (material-design-icons)

#####Potential changes
I am considering the following changes:
* MongoDB -> ArangoDB
* Angular -> Flux + React
* Express -> Koa
* Selenium WebDriver -> Phantom
* Grunt -> Gulp
* Bootstrap -> Material Design

###Team
Tyler Mace (tylerdmace)

# Contributing
I still don't know the best way to do this so I'm experimenting. If unsure about process or if you have a better suggestion, please let me know (@tylerdmace).

###Create new issue
Create a new issue on Github where the development can be discussed

###Fork, clone, and branch
When you branch, you'll do so from the default `develop` branch and you'll follow the below standard:

`<initials>/<action>/<issue-number>`

An example of this would be myself adding a new feature which I have created an issue for (let's say it is issue #13):

```Bash
$ git checkout -b tdm/add/issue-13
```

* `tdm` are my initials
* `add` since I am adding a new feature; other actions might be `remove`, `bug-fix`, or `update`
* `issue-13` matches the issue number created in Github

# Development
### Requirements
* Node (for NPM)
* MongoDB

### Installation
Pretty simple setup. Ensure that you've got `mongod` running and bound to the default port, then:

```Bash
$ npm install
```
And to start the server:

```Bash
$ grunt
```
#####Database Seed
To provide kindling with a database seed:

```Bash
$ mongoimport kindling-seed.json
```
# Changelog
The kindling changelog can be found in `ChangeLog` and is viewable here: https://github.com/tylerdmace/kindling/blob/master/ChangeLog
