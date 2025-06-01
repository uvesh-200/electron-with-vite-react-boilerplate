# Electron with Vite React

A modern and robust boilerplate for building cross-platform desktop applications using Electron, Vite, and React with TypeScript. This project provides a streamlined development experience with fast build times and hot module replacement, making it an ideal starting point for your next desktop app.

## Features

-   ⚡️ **Vite**: Lightning-fast development server and optimized production builds.
-   ⚛️ **React 19**: Latest version of React for building dynamic user interfaces.
-   🖥️ **Electron**: Framework for creating native desktop applications with web technologies.
-   📦 **Electron Builder**: Comprehensive solution for packaging and distributing your Electron app across Windows, macOS, and Linux.
-   🔥 **Hot Module Replacement (HMR)**: Instant updates during development without full page reloads.
-   🎨 **TypeScript**: Enhanced code quality and developer experience with static typing.
-   📝 **ESLint**: Configured for code consistency and error prevention.
-   ⚙️ **Concurrent Development**: Seamlessly run Vite and Electron simultaneously.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

-   **Node.js**: Version 18 or higher (LTS recommended).
    -   You can download it from [nodejs.org](https://nodejs.org/).
-   **npm**: Node Package Manager (comes bundled with Node.js).

## Installation

To get this project up and running on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/uvesh-200/electron-with-vite-react-boilerplate.git
    cd electron-with-vite-react
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

## Development

To start the development server and launch the Electron application in development mode:

```bash
npm run dev
```

This command will:
-   Start the Vite development server for your React frontend.
-   Launch the Electron application, which will load the Vite development server.
-   Enable hot module replacement, allowing you to see changes in your React code instantly without restarting the Electron app.

## Building for Production

To create a production-ready build of your React frontend:

```bash
npm run build
```

This command compiles your React application into static files, optimized for performance, and places them in the `dist` directory.

## Packaging the Application

To package your Electron application for distribution (e.g., as an installer for Windows, macOS, or Linux):

```bash
npm run package
```

This command will:
1.  First, run `npm run build` to create the production build of your frontend.
2.  Then, use `electron-builder` to package the Electron application.
3.  **The generated installers and executables will be placed in the `dist` directory at the root of your project.**

    For example, on Windows, you might find an `.exe` installer (e.g., `MyElectronApp Setup 1.0.0.exe`) inside `dist`. On macOS, you'd find a `.dmg` or `.app` file.

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run package` - Build and package the application


## Support

For support, email uveshchapti@gmail.com or open an issue in the repository.