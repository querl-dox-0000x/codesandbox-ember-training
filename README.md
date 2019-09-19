# my-app

This README outlines the details of collaborating on this Ember application.
A short introduction of this app could easily go here.

## Export path

export PATH=\$PATH:/usr/local/bin:/usr/bin:/bin:/usr/local/games:/usr/games:/sandbox/node_modules/.bin

## Create bash_profile

echo 'export PATH=\$PATH:/usr/local/bin:/usr/bin:/bin:/usr/local/games:/usr/games:/sandbox/node_modules/.bin' >> ~/.bash_profile && source ~/.bash_profile

## Add to scripts
 "scripts": {
   
   "bash_profile": "echo 'export PATH=$PATH:/usr/local/bin:/usr/bin:/bin:/usr/local/games:/usr/games:/sandbox/node_modules/.bin' >> ~/.bash_profile && . ~/.bash_profile"
    
  },

## Prerequisites

You will need the following things properly installed on your computer.

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (with npm)
- [Ember CLI](https://ember-cli.com/)
- [Google Chrome](https://google.com/chrome/)

## Installation

- `git clone <repository-url>` this repository
- `cd my-app`
- `npm install`

## Running / Development

- `ember serve`
- Visit your app at [http://localhost:4200](http://localhost:4200).
- Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

- `ember test`
- `ember test --server`

### Linting

- `npm run lint:hbs`
- `npm run lint:js`
- `npm run lint:js -- --fix`

### Building

- `ember build` (development)
- `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

- [ember.js](https://emberjs.com/)
- [ember-cli](https://ember-cli.com/)
- Development Browser Extensions
  - [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  - [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
