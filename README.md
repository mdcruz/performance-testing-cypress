# Performance Testing Using Cypress.io

Supporting materials for my session on Automation Guild 2021 where I will share how to extend Cypress to test for web performance.

## Pre-requisites

- [Node and NPM](https://nodejs.org/en/download/) [LTS version]
- [Visual Studio Code](https://code.visualstudio.com/download) or any text editor of your choice

## Getting Started

To get started on the hands-on material, simply clone this repository, `cd` to the project root and then install the project dependencies by typing in `npm i` on your chosen terminal.

## Running The Tests

To open the Cypress Test Runner, simply type `npx cypress open` and select the file that you want to run.

Alternatively, to run it headlessly on Chrome, type `npx cypress run --browser chrome --headless`

## Links from the recorded session

1. [cypress-audit](https://github.com/mfrachet/cypress-audit)
2. [lighthouse-cli](https://github.com/GoogleChrome/lighthouse)
3. [Cypress Browser Launch API](https://docs.cypress.io/api/plugins/browser-launch-api.html#Syntax)
4. [Lighthouse Emulation](https://github.com/GoogleChrome/lighthouse/blob/master/docs/emulation.md)
