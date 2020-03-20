# cra-template-csandman

This is the base template used by me, CSandman.

### Features

This template uses a simple set of default tools to get you up and running
quickly and have a consistent development environment accross a team. This
template reflects the guide I wrote on getting set up with React, ESLint, and
Prettier which [can be read here](https://csandvik.com/react-prettier-eslint/).
Here is a list of the features used by this template:

- ESLint using the Airbnb style guide
  - One exception to this is the all lowercase filenames as specified in the
    Google Javascript styleguide
- Prettier with mostly defaults other than `"singleQuote"` set to true
- Absolute imports for your `/src` folder
- SCSS support with `node-sass`

### Setup

To create a new react app using this templata, run the following command:

```
npx create-react-app my-app-name --template csandman
```
