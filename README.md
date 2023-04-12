# Markdown Viewer (for markdown prompts)

This is a Markdown viewer web application that allows users to search and view Markdown files with syntax highlighting.

## Features

- Syntax highlighting for code blocks
- Search functionality using Flexsearch and Fuzzysort
- User-friendly interface with responsive layout
- Customizable appearance using CSS

## Usage

1.  Clone the repository or download the source code.
2.  Add your Markdown files to the project folder.
3.  In markdown directory, add `prompts.html`
4.  run `npx serve`, assuming node and npm is installed
5.  navigate to http://localhost:3000/prompts
6.  Use the search bar to find specific content within the Markdown files.

## Dependencies

The following libraries are used in this project:

- [marked](https://github.com/markedjs/marked): A Markdown parser and compiler.
- [highlight.js](https://github.com/highlightjs/highlight.js): A syntax highlighter for the web.
- [fuzzysort](https://github.com/farzher/fuzzysort): A fast SublimeText-like fuzzy search for JavaScript.
- [flexsearch](https://github.com/nextapps-de/flexsearch): A fast full-text search library.

## Customization

You can customize the appearance of the Markdown viewer by modifying the CSS styles in the `<style>` section of the `index.html` file.

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
