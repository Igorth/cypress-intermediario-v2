# cypress-intermediate

We will test a complex application for the [**TAT School Cypress Intermediate course**](https://udemy.com/user/walmyr). This application is an open-source version of GitLab, running in a container in your local environment.

## Pre-requirements

It is required to have Node.js, npm, git and Docker installed to run this project.

- [Docker](https://www.docker.com/) ( I'm using the version `24.0.5` )
- [git](https://git-scm.com/) ( I'm using the version `2.39.2` )
- [Node.js](https://nodejs.org/en/) ( I'm using the version `v18.17.1` )
- npm ( I'm using the version `9.6.7` )

>I recommend using the same or more recent versions of the systems listed above.
>
>To check the versions of Docker, git, Node.js, and npm installed on your computer, run the command `docker --version && git --version && node --version && npm --version` in your command-line terminal.

Before you begin, ensure the following requirements are met:

- Computer with at least 2 cores
- and at least 8 GB of RAM

## Installation

Run `npm install` (or `npm i` for the short version) to install the dev dependencies.

## Tests

Run `npm test` (or `npm t` for the short version) to run the test in headless mode.

Or, run `npm run cy:open` to open Cypress in interactive mode.

## What will you learn

During the automated testing course with Cypress (intermediate), you will learn the following:

- How to configure the local development environment
- How to install and configure Cypress
- How to create automated graphical user interface tests
- How to create automated API tests (with visual _feedback_ in the browser)
- How to test APIs that require an access _token_
- How to create optimized and straight-to-the-point tests
- How to save the user session in the browser for later restoration
- How to validate if the user session is still valid and how to deal with it when it is invalidated
- How to clean and create the mass of data before testing begins
- How to protect sensitive data, such as passwords and access tokens
- How to organize tests and custom commands into different "layers" (_API, CLI, GUI_)
- How to structure tests thinking about preconditions, actions and expected results
- How to generate random data for use in automated tests
- How to enable experimental Cypress features
- How to execute commands at the operating system level
- And how to test file reading
___

This project was created with ❤️ by [Igor Dias](https://igordiasth.dev).