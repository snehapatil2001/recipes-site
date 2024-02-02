# Foodies Recipes Site

This project is a simple recipe website built with Tailwind CSS. It showcases a responsive grid layout for displaying recipes, a navigation menu, and some styling using Tailwind utility classes.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installing Dependencies](#installing-dependencies)
  - [Building CSS](#building-css)
- [Project Structure](#project-structure)

## Technologies Used

- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework.
- [Google Fonts - Nunito](https://fonts.google.com/specimen/Nunito): Used for the body font.

## Getting Started

### Prerequisites

Before you begin, make sure you have the following installed:

- [Node.js](https://nodejs.org/): The JavaScript runtime.
- [npm](https://www.npmjs.com/): The Node.js package manager.

### Installing Dependencies

- #### Clone the repository: git clone https://github.com/your-username/recipes-site.git recipes-site
- #### Navigate to the project directory: cd recipes-site

### Building CSS

1. Install dependencies:

    ```bash
    npm install
    ```

2. Build CSS using Tailwind CSS:

    ```bash
    npm run build-css
    ```

3. Open `public/index.html` in your web browser to view the recipe site.

### Project Structure

- **tailwind.config.js:** Tailwind CSS configuration file with custom colors, fonts, and content settings.

- **package.json:** Node.js project configuration file specifying dependencies and scripts. It includes Tailwind CSS and Prettier as devDependencies.

- **.prettierrc.json:** Configuration file for Prettier with the `prettier-plugin-tailwindcss` plugin.

- **src/styles.css:** Main CSS file for styling the project. It includes Tailwind CSS imports, custom styles, and utility classes.

- **public/index.html:** Main HTML file containing the structure of the recipe site. It uses Tailwind CSS classes for styling and responsiveness.

- **public/index.js:** JavaScript file for handling the mobile menu toggle.
