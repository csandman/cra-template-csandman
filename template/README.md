# cra-template-csandman

This is the base
[Create React App](https://github.com/facebook/create-react-app). template used
by me, CSandman.

## Features

This template uses a simple set of default tools to get you up and running
quickly and have a consistent development environment accross a team. This
template reflects the guide I wrote on getting set up with React, ESLint, and
Prettier which [can be read here](https://csandvik.com/react-prettier-eslint/).
Here is a list of the features used by this template:

- ESLint using the Airbnb style guide
  - One exception to this is the all lowercase filenames as specified in the
    Google Javascript styleguide
- Prettier with mostly defaults other than `"singleQuote"` set to true
- Absolute imports for your `src/` folder which allows you to import any project
  files with `import MyComponent from 'components/my-component`
- SCSS support with `node-sass`

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
