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

To watch the SASS files for changes and re-compile:

```shell
npm install
npm run sass-watch
```

## Compile and copy CSS files to the PrimeReact repository

Usually you want to update the CSS files in the PrimeReact repository, located in the
`/primereact/public/themes` folder. To do so you can use the following scripts.

These scripts asume that the PrimeReact repository is located next to this repository, so at `../primereact`.
They will compile the CSS files and copy the resulting CSS files to the correct resources folders.

### Unix

```shell
./build.sh
```

### Windows

```shell
build.bat
```

# About the fork

[As per instructions here](https://primereact.org/theming/#customtheme), we must copy the contents from `mytheme` to our projects. This approach would cut the updates to the saas theme.
We choose to fork the repo, and apply our brand colors. This way when there's an update we will merge latest changes in our theme (in this repository).

# How to tweak the variables

1. Change the variables from `mytheme`
2. run the `saas` command to compile the `theme.css` (more details in above links)
3. copy the resulting `theme.css` in `fabled-kit`