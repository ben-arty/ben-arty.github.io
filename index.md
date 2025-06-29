---
layout: "default"
title: "Next.js Full Stack Template for Rapid Development 🚀"
description: "Modern Next.js stack template with TypeScript and Tailwind CSS. Features include shadcn/ui components, ESLint, Jest, and Sentry integration. 🚀🌟"
---
# Next.js Full Stack Template for Rapid Development 🚀

![Next.js](https://img.shields.io/badge/Next.js-15-brightgreen)
![TypeScript](https://img.shields.io/badge/TypeScript-4.5-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-2.2-purple)
![React](https://img.shields.io/badge/React-17.0%20%7C%20%3E%3D%2017.0-orange)
![Jest](https://img.shields.io/badge/Jest-27.0%20%7C%20%3E%3D%2027.0-yellow)
![Sentry](https://img.shields.io/badge/Sentry-6.0%20%7C%20%3E%3D%206.0-red)

---

## Overview

Kickstart your next web project with this robust Next.js Full Stack Template. This template provides a solid foundation for building modern web applications using Next.js, TypeScript, and Tailwind CSS. It includes essential tools and configurations to streamline your development process.

You can find the latest releases [here](https://github.com/ben-arty/nextjs-stack-template/releases). Make sure to download and execute the necessary files to get started quickly.

---

## Features

- **Next.js 15**: Build fast and scalable applications with server-side rendering and static site generation.
- **TypeScript**: Enjoy type safety and better developer experience.
- **Tailwind CSS**: Create beautiful, responsive designs with utility-first CSS.
- **Jest**: Write tests for your components and ensure quality.
- **Sentry**: Monitor your application for errors and performance issues.
- **Husky**: Enforce Git hooks for better code quality.
- **Commitlint**: Maintain a consistent commit message style.
- **ESLint**: Keep your code clean and consistent.
- **Prettier**: Automatically format your code for readability.
- **Lucide React**: Use a collection of open-source icons.
- **Shadcn UI**: Access a set of accessible components for your app.

---

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (version 14 or later)
- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ben-arty/nextjs-stack-template.git
   ```

2. Navigate to the project directory:

   ```bash
   cd nextjs-stack-template
   ```

3. Install the dependencies:

   Using npm:

   ```bash
   npm install
   ```

   Or using yarn:

   ```bash
   yarn install
   ```

### Running the Development Server

To start the development server, run:

```bash
npm run dev
```

Or if you prefer yarn:

```bash
yarn dev
```

Visit `http://localhost:3000` in your browser to see your application in action.

### Building for Production

To create an optimized production build, run:

```bash
npm run build
```

Or with yarn:

```bash
yarn build
```

Then, start the production server:

```bash
npm start
```

Or with yarn:

```bash
yarn start
```

---

## Configuration

### Environment Variables

Create a `.env.local` file in the root of your project to store environment variables. This file should not be committed to version control. Here’s an example:

```
NEXT_PUBLIC_API_URL=https://api.example.com
SENTRY_DSN=your_sentry_dsn
```

### ESLint Configuration

You can customize ESLint rules in the `.eslintrc.js` file. Make sure to follow best practices to maintain code quality.

### Prettier Configuration

Adjust Prettier settings in the `.prettierrc` file to fit your coding style preferences.

---

## Testing

### Running Tests

To run the tests, use the following command:

```bash
npm test
```

Or with yarn:

```bash
yarn test
```

This will execute all tests defined in your project. You can also run tests in watch mode with:

```bash
npm test -- --watch
```

Or:

```bash
yarn test --watch
```

### Writing Tests

Tests are located in the `__tests__` directory. Follow the structure to add your own tests. Make sure to cover your components and pages.

---

## CI/CD Integration

Integrate your project with CI/CD tools like GitHub Actions or Travis CI to automate testing and deployment. Here’s a basic example for GitHub Actions:

1. Create a `.github/workflows/ci.yml` file.

2. Add the following content:

   ```yaml
   name: CI

   on:
     push:
       branches:
         - main
     pull_request:
       branches:
         - main

   jobs:
     build:
       runs-on: ubuntu-latest

       steps:
       - name: Checkout code
         uses: actions/checkout@v2

       - name: Set up Node.js
         uses: actions/setup-node@v2
         with:
           node-version: '14'

       - name: Install dependencies
         run: npm install

       - name: Run tests
         run: npm test
   ```

---

## Contribution

We welcome contributions to improve this template. Here’s how you can help:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Open a pull request with a clear description of your changes.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Jest Documentation](https://jestjs.io/docs/getting-started)
- [Sentry Documentation](https://docs.sentry.io/)
- [Husky Documentation](https://typicode.github.io/husky/#/)
- [Commitlint Documentation](https://commitlint.js.org/#/)

For more information and updates, check the [Releases](https://github.com/ben-arty/nextjs-stack-template/releases) section.

---

## Acknowledgments

Thank you to the open-source community for providing the tools and libraries that make this project possible. Special thanks to the contributors who help improve this template.

---