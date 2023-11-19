# My SCSS Project

This is a project that follows the 7-1 architecture pattern for organizing SCSS files. The 7-1 pattern is a common structure for organizing SCSS files in a project. It's organized into 7 folders for partial Sass files, and 1 file for the main Sass file.

## Project Structure

The project is structured as follows:

- `abstracts`: Contains SCSS variables and functions that are used throughout the project.
- `base`: Contains base styles, such as resets and typography rules.
- `components`: Contains styles for individual components, like buttons.
- `layout`: Contains styles for larger layout components, like headers and footers.
- `pages`: Contains page-specific styles.
- `themes`: Contains styles for different themes.
- `vendors`: Contains third-party styles, like Bootstrap.
- `main.scss`: The main SCSS file that imports all other SCSS files.

## How to Use

To use this project, you need to have Sass installed on your machine. If you don't have Sass installed, you can install it by following the instructions on the [official Sass website](https://sass-lang.com/install).

Once you have Sass installed, you can compile the SCSS files into CSS by running the following command in the root directory of the project:

```bash
sass sass/main.scss:main.css
```

This will compile the `main.scss` file into a `main.css` file that you can include in your HTML.

## Contributing

If you want to contribute to this project, please make sure to follow the existing file and folder structure. Add your SCSS files to the appropriate folder and import them in the `main.scss` file.