# cra-template-csandman

This is the base template for
[create-react-app](https://github.com/facebook/create-react-app) created by and
for [csandman](https://github.com/csandman).

## Features

This template uses a simple set of default tools to get you up and running
quickly and have a consistent development environment accross a team. This
template reflects the guide I wrote on getting set up with React, ESLint, and
Prettier which [can be read here](https://csandvik.com/react-prettier-eslint/).
Here is a list of the features used by this template:

- ESLint using the Airbnb style guide
  - One exception to this is the all lowercase filenames as specified in the
    Google Javascript styleguide. I am not sure why Airbnb chooses to name all
    files in the same case as the component but it goes against the pattern of
    every package I've downloaded from NPM.
- Prettier with mostly defaults other than `"singleQuote"` set to true
- Absolute imports for your `src/` folder
- SCSS support with `node-sass`
- Barreling for individual components to prevent the import syntax from being
  `import ComponentA from 'components/component-a/component-a'`

## Available Scripts

This template offers the following custom scripts in addition to the default
create-react-app scripts.

### `npm run format`

This will format all compatible files in the `src/` directory with the included
`.prettierrc` config.

### `npm run lint`

This will run eslint on all of the `.js` and `.jsx` files inside of the `src/`
directory using the config defined in `.eslintrc`.

### `npm run clean-install`

This should only be used if you run into any issues with your node_modules
installation. It is a shortcut to removing your `package-lock.json` (or
`yarn.lock`) and your `node_modules/` folder and runnning a fresh install.
