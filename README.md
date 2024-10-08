# Password Generator

A simple password generator built with React, Vite, and Tailwind CSS. This application allows users to generate a random password with customizable options like length, inclusion of numbers, and special characters.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [Scripts](#scripts)
- [License](#license)

## Installation

To get started with this project, you'll need to have Node.js and npm installed on your machine. Then, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/password-generator.git
   cd password-generator
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

## Usage

To start the development server and see the application in action, run:

```bash
npm run dev
```

This will start the Vite development server and open the application in your default browser at `http://localhost:3000`.

## Project Structure

The project is structured as follows:

```bash
.
├── public/             # Public assets
├── src/                # Source files
│   ├── App.css         # Tailwind CSS imports and custom styles
│   ├── App.jsx         # Main application component
│   ├── index.css       # Global CSS file
│   ├── main.jsx        # Application entry point
│   └── ...
├── index.html          # Main HTML file
├── package.json        # Project metadata and scripts
├── tailwind.config.js  # Tailwind CSS configuration file
└── vite.config.js      # Vite configuration file
```

## Configuration

### Setting Up Tailwind CSS

This project is configured with Tailwind CSS. Here's how you can set it up if you start a new project from scratch:

1. **Install Tailwind CSS:**

   First, install Tailwind CSS, PostCSS, and Autoprefixer:

   ```bash
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init -p
   ```

2. **Configure `tailwind.config.js`:**

   The `tailwind.config.js` file is automatically generated by the `tailwindcss init -p` command. Here's an example configuration:

   ```javascript
   module.exports = {
     content: ['./index.html', './src/**/*.{js,ts,jsx,tsx}'],
     theme: {
       extend: {},
     },
     plugins: [],
   }
   ```

3. **Add Tailwind Directives to CSS:**

   In your `src/index.css` or `App.css`, add the Tailwind directives:

   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

4. **Start the Development Server:**

   Run the development server to see Tailwind CSS in action:

   ```bash
   npm run dev
   ```

### Customizing Tailwind CSS

You can customize your Tailwind setup in the `tailwind.config.js` file by adding custom themes, plugins, or modifying the default configuration.

## Scripts

- **`npm run dev`**: Starts the development server.
- **`npm run build`**: Builds the app for production.
- **`npm run serve`**: Serves the production build locally.

## License

This project is licensed under the MIT License.
