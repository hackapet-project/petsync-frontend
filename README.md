# PetSync Frontend
[English](README.md) | [Español](README.es.md)

![PetSync Logo](readme/thumbnail.png)

Frontend for the PetSync project, built with React and TypeScript.

## Table of Contents
1. [Project Purpose](#project-purpose)
2. [Technologies](#technologies)
3. [Environment Setup](#environment-setup)
   - [Node.js and npm](#nodejs-and-npm)
   - [Git](#git)
   - [GitHub Account](#github-account)
   - [Code Editor](#code-editor)
4. [Installation Instructions](#installation-instructions)
   - [Install Node.js and npm](#install-nodejs-and-npm)
   - [Install Git](#install-git)
   - [Clone the Repository](#clone-the-repository)
   - [Install Dependencies](#install-dependencies)
5. [Running the Application](#running-the-application)
6. [Testing](#testing)
7. [Building for Production](#building-for-production)
8. [Additional Resources](#additional-resources)

## Project Purpose
PetSync Frontend is the user interface for the PetSync project, an application designed to optimize animal shelter management. It provides an intuitive and responsive interface for shelter staff to manage animals, inventory, and generate reports.

Key features:
- Dashboard for quick overview of shelter status
- Animal management interface
- Inventory tracking system
- Reporting and analytics tools

## Technologies
- React
- TypeScript
- Redux for state management
- React Router for navigation
- Styled Components for styling
- Jest and React Testing Library for testing

## Environment Setup
### Node.js and npm
Node.js is required to run the project, and npm (Node Package Manager) is used to manage dependencies.

### Git
Git is used for version control.

### GitHub Account
A GitHub account is needed to access the repository and collaborate on the project.

### Code Editor
We recommend using Visual Studio Code, but any modern code editor with TypeScript support will work.

## Installation Instructions

### Install Node.js and npm
1. Visit the [official Node.js website](https://nodejs.org/).
2. Download and install the LTS version for your operating system.
3. Verify the installation by opening a terminal and running:
   ```
   node --version
   npm --version
   ```

### Install Git
#### On Windows:
1. Download Git from [git-scm.com](https://git-scm.com/download/win).
2. Run the installer and follow the setup wizard.

#### On macOS:
1. Install Homebrew if you haven't already:
   ```
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
2. Install Git using Homebrew:
   ```
   brew install git
   ```

#### On Linux:
Use your distribution's package manager. For Ubuntu or Debian:
```
sudo apt-get update
sudo apt-get install git
```

### Clone the Repository
1. Open a terminal.
2. Navigate to the directory where you want to store the project.
3. Clone the repository:
   ```
   git clone https://github.com/hackapet-project/petsync-frontend.git
   ```
4. Navigate into the project directory:
   ```
   cd petsync-frontend
   ```

### Install Dependencies
In the project directory, run:
```
npm install
```

## Running the Application
To start the development server:
```
npm start
```
The application will be available at `http://localhost:3000`.

## Testing
To run the test suite:
```
npm test
```

## Building for Production
To create a production build:
```
npm run build
```

## Additional Resources
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Redux Documentation](https://redux.js.org/introduction/getting-started)
- [Project Wiki](https://github.com/hackapet-project/petsync-frontend/wiki)

For more information or if you encounter any issues, please refer to our [wiki](https://github.com/hackapet-project/petsync-frontend/wiki) or open an issue in the repository.
