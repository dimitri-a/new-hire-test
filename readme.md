# Macquarie Code Challenge

Congratulations on making it this far!
We are now going to be examining your coding abilities.

### Introduction

We will keep the examination fairly short as we appreciate that your time is valuable. It should take no more than 1-2 hours.
We will be doing most of the boilerplate code so that you will not need to spend time setting things up.

### Skills we are examining

- Responsive design (for this demo we will be using bootstrap as our css framework)
- JavaScript
- AngularJS (do **not** include jQuery or any other library)
- Automated testing of JavaScript
- Git

### Things we will be looking for

- Simple, testable, readable code
- Good JavaScript and AngularJS practices

### Do not do too much!

This is only a demo, do not break yourself! If something is taking too long,
leave it and we can discuss it later.

A few things you don't have to worry about in order to keep the time down:

- jshint (although you are welcome to include it to ensure your code consistency)
- concatenation
- minification
- cross browser support (*we will be reviewing on the latest version of chrome*)
- comprehensive testing (a few will be fine)

### System Prerequisites

- node
- npm
- bower
- sass
- grunt

## Setup

1. Fork this repository
2. Create a new branch titled - 'my-feature-request'
3. run `npm i` and `bower i` to install dependencies
4. Create your application code and tests (see below)
5. Send us a link to your branch when you are finished

### Development

This project uses `grunt` to build the sass files
To build the css run `grunt` or `grunt default`
The sass will automatically recompile for you if you run `grunt watch`

## Requirements

We are looking to make a simple staff search application.
As the user types a *search query* the matching results are shown

#### Desktop view:


![Desktop View](https://bitbucket.org/cogddt/new-hire-test/raw/master/documentation/desktop.png)

#### Mobile view:

![Mobile View](https://bitbucket.org/cogddt/new-hire-test/raw/master/documentation/mobile.png)


When the user types in the search box it should filter the results

the query will be in the form:
`'property:value prop2:value2'`
Example:
`'name:alex'`
`'office:sydney role:teacher'`

If no results are found the *error view* is shown

![Multi Selection](https://bitbucket.org/cogddt/new-hire-test/raw/master/documentation/multi-find.png)


#### Error view

![Error View](https://bitbucket.org/cogddt/new-hire-test/raw/master/documentation/error.png)

### Staff data

```
var data = [
        {
            name: 'Alex',
            role: 'Developer',
            office: 'Sydney'
        },
        {
            name: 'Ben',
            role: 'Developer',
            office: 'Wogga'
        },
        {
            name: 'Sam',
            role: 'Teacher',
            office: 'Sydney'
        },
        {
            name: 'Steve',
            role: 'Builder',
            office: 'Melbourne'
        },
        {
            name: 'Josh',
            role: 'Driver',
            office: 'Sydney'
        },
        {
            name: 'Sarah',
            role: 'Lawyer',
            office: 'Brisbane'
        }
    ];
```
For avatars use:
``http://api.adorable.io/avatars/120/[ persons name goes here ]@adorable.png``

