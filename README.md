[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# PrimeReact Theming with SASS

Visit the [official documentation](https://primereact.org/theming/#customtheme) for more information.

<img src="https://upload.wikimedia.org/wikipedia/commons/9/96/Sass_Logo_Color.svg" height="100" alt="SASS Logo" />

## Usage

To compile the CSS once:

```shell
npm install
npm run sass
```

# About the fork

[As per instructions here](https://primereact.org/theming/#customtheme), we must copy the contents from brand theme `avask/simplyvat` to our projects. This approach would cut the updates to the saas theme.
We choose to fork the repo, and apply our brand colors. This way when there's an update we will merge latest changes in our theme (in this repository).

# How to tweak the variables

1. Change the variables from `avask` or other theme
2. run the `saas` command to compile the `theme.css`.
   - 2.1 `npm run sass --update themes/simplyvat/theme.scss:themes/simplyvat/theme.css`
   - 2.2 `npm run sass --update themes/avask/theme.scss:themes/avask/theme.css`
3. copy the resulting `theme.css` to `fabled-kit`
