
# Advanced Text Editor

An advanced text editor built with React and TypeScript that allows you to dynamically load fonts, adjust font size, and style the text.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Advanced Text Editor is a React application that enables users to select fonts dynamically, adjust font weights, toggle italics, and change font sizes. This editor persists the user's text and formatting choices using `localStorage`, providing a seamless experience even after refreshing the page.

## Features

- **Dynamic Font Loading**: Load and apply fonts dynamically using `webfontloader`.
- **Font Weight and Italic Toggle**: Choose different font weights and toggle italic styles.
- **Font Size Adjustment**: Select from various font sizes.
- **State Persistence**: Save and load the editor's state using `localStorage`.

## Installation

Follow these steps to set up and run the project locally.

### Prerequisites

Make sure you have the following installed on your system:

- Node.js (version 14 or later)
- npm (version 6 or later)

### Steps

1. **Clone the Repository**

   ```sh
   git clone https://github.com/RajoliPavaniReddy/text-editor.git
   cd text-editor
   ```

2. **Install Dependencies**

   ```sh
   npm install
   ```

3. **Run the Application**

   ```sh
   npm start
   ```

   This will start the development server and open the application in your default web browser.

## Usage

1. **Select a Font**

   - Choose a font from the dropdown menu.
   - The font options are loaded from a `fonts.json` file located in the `public` directory.

2. **Adjust Font Weight and Toggle Italic**

   - Select the desired font weight from the dropdown menu.
   - Check the italic checkbox to apply italic styling.

3. **Select Font Size**

   - Choose the font size from the dropdown menu.

4. **Type in the Textarea**

   - Start typing in the textarea to see the applied styles.
   - The editor's state (text and styles) is saved automatically and will persist across page reloads.

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. **Fork the Repository**

   - Click the "Fork" button at the top right of the repository page to create a copy of the repository under your GitHub account.

2. **Clone Your Fork**

   ```sh
   git clone https://RajoliPavaniReddy/texteditor.git
   cd your-repository
   ```

3. **Create a Branch**

   ```sh
   git checkout -b feature-branch
   ```

4. **Make Your Changes**

   - Implement your changes and additions.

5. **Commit Your Changes**

   ```sh
   git add .
   git commit -m 'Add some feature'
   ```

6. **Push to Your Branch**

   ```sh
   git push origin feature-branch
   ```

7. **Open a Pull Request**

   - Go to the original repository on GitHub and click the "New pull request" button.
   - Provide a clear description of your changes and submit the pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

```

### Additional Steps

1. **Replace Placeholder Text**: Ensure you replace `your-username` and `your-repository` with your actual GitHub username and repository name.
2. **Add Screenshots**: Consider adding screenshots or a demo GIF to the `README.md` to visually showcase your application.
3. **Additional Sections**: Add any additional sections specific to your project, such as known issues, troubleshooting, or acknowledgments.

### Committing and Pushing the README

Add and commit the `README.md` file to the repository, then push it to GitHub.

```sh
git add README.md
git commit -m "Add detailed README file"
git push
```

By following these steps, you'll have a comprehensive and informative `README.md` file for your project on GitHub.
