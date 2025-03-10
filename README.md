# CodebaseAngular

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.0.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

## Setting up Tailwind CSS

Here's how to set up Tailwind CSS in your project:

## 1. Install Tailwind CSS and its dependencies

```bash
# Sử dụng npm
npm install -D tailwindcss@3.4.1 postcss@8.4.35 autoprefixer@10.4.17

# Hoặc sử dụng yarn
yarn add -D tailwindcss@3.4.1 postcss@8.4.35 autoprefixer@10.4.17

npx tailwindcss init -p
```

This installs Tailwind CSS, PostCSS, and Autoprefixer, then creates both `tailwind.config.js` and `postcss.config.js` files.

## 2. Configure your template paths

Edit your `tailwind.config.js` file to tell Tailwind which files to scan for class usage:

```js:tailwind.config.js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{html,ts}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

Adjust the `content` paths to match your project structure.

## 3. Add the Tailwind directives to your CSS

Create or update your main CSS file (often `src/index.css` or similar) with:

```styles.scss
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Would you like me to provide more specific setup instructions for a particular framework (React, Vue, Next.js, etc.)?
