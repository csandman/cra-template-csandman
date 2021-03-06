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
  - All prettier configs are defined for 2 reasons. The first is that if you're
    developing on a team, any individual team member's IDE specific settings
    would override the defaults. And the second is that if you update prettier
    and they change some of the defaults (like with version 2.0.0) things will
    start to change in ways you might not want. You can easily change these
    defaults if you'd like by editing the `.prettierrc` file.
- Absolute imports for your `src/` folder
- SCSS support with `node-sass`
- Barreling for individual components to prevent the import syntax from being
  `import ComponentA from 'components/component-a/component-a'`. I'm still not
  sold on this strategy but that redundent import sytax really bugs me.

## Setup

To create a new react app using this templata, run the following command:

```
npx create-react-app my-app-name --template csandman
```

Optionally add the flag `--use-npm` if you have yarn installed on your computer
and prefer to use npm. I am in this boat and just recently learned about this
flag, so it might help others too.
