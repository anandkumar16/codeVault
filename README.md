# CodeVault

CodePaste is a web application built with React, Vite, and Tailwind CSS that allows users to create, update, delete, and view code snippets. The application features a user-friendly interface, state management with Redux Toolkit.

## Features

- **Create Code Pastes**: Users can create new code snippets with titles and content.
- **Update Code Pastes**: Existing code snippets can be updated by editing the title and content.
- **Delete Code Pastes**: Users can remove unwanted code snippets from their collection.
- **View Code Pastes**: Users can view individual code snippets in detail.
- **Search Functionality**: Quickly find pastes by searching through titles and content.


## Installation

### Step 1: Create a Vite project

1. Install Vite globally (if not already installed):

   ```bash
   npm create vite@latest
   ```

2. When prompted, choose the following:
   - Project name: `paste`
   - Framework: `React`
   - Variant: `JavaScript` or `TypeScript` as per your preference.

3. Navigate into the project directory:

   ```bash
   cd paste
   ```

### Step 2: Install Tailwind CSS

To add Tailwind CSS to your Vite + React project, follow these steps:

1. Install Tailwind CSS and its dependencies:

   ```bash
   npm install -D tailwindcss postcss autoprefixer
   ```

2. Initialize Tailwind configuration:

   ```bash
   npx tailwindcss init
   ```

   This will create a `tailwind.config.js` file in your project.

3. Update the `tailwind.config.js` file with the following content to specify which files Tailwind should scan:

   ```js
   /** @type {import('tailwindcss').Config} */
   export default {
     content: [
       './index.html',
       './src/**/*.{js,ts,jsx,tsx}',
     ],
     theme: {
       extend: {},
     },
     plugins: [],
   }
   ```

4. Add the following lines to your `src/index.css` (or `src/main.css` if you’re using that):

   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

### Step 3: Install Required Packages

Install the project dependencies:

```bash
npm install
```

### Step 4: Run the Project

Start the development server with the following command:

```bash
npm run dev
```

This command will launch the development server, and your project will be available at `http://localhost:5173`.

## Scripts

- **`npm run dev`**: Starts the Vite development server with HMR.
- **`npm run build`**: Builds the project for production.
- **`npm run preview`**: Serves the production build for preview.
- **`npm run lint`**: Lints your code using ESLint.


## Conclusion

Codevaultis a powerful tool for managing code snippets, providing a seamless experience for creating, updating, deleting, and viewing pastes. With its modern tech stack and responsive design, it is an excellent choice for developers looking to organize their code snippets efficiently. Feel free to customize it further according to your project requirements!
