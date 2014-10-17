[![Build Status](https://travis-ci.org/meanjs/mean.svg?branch=master)](https://travis-ci.org/meanjs/mean)
[![Dependencies Status](https://david-dm.org/meanjs/mean.svg)](https://david-dm.org/meanjs/mean)

kindling is a Tinder clone that supports swipe-undo

# About

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
* Node
* Bower
* MongoDB

### Installation
Pretty simple setup. Ensure that you've got a mongo server running on the default port, then:

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
