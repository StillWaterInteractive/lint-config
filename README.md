# Still Water Code Style

> Common Eslint and Prettier config we use at Still Water ✨

A setup for Eslint and Prettier that we've adopted at Still Water for our projects.

We extend the [Airbnb style guide](https://github.com/airbnb/javascript/) with a couple rules tweaked or turned off.

Our code style can be summed up as:

- Indent lines with spaces, not tabs
- Use single quotes, not double
- Spaces between brackets in object literals
- Semi-colons at the end of statements
- No trailing commas
- Don't include parenthesis around a sole arrow function parameter

## Usage

Clone the repo (or alternatively, just download a zip from Github):

```
git clone git@github.com:StillWaterInteractive/lint-config.git
```

Then copy the `package.json` and dotfiles into the new project, and install dependencies:

```
yarn install
```

And you're good to go!

## 🔺 Note

If you're integrating linting into an existing project and don't want to copy files over, you can just run the following command to install the required dependencies:

```
yarn add eslint eslint-config-airbnb eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react husky lint-staged prettier -D
```
