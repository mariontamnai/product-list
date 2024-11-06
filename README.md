# Product List App

A React-based web application that helps users manage and track product lists efficiently. Users can add, edit, and delete products while maintaining an organized and user-friendly interface.

---

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

---

## Description

The **Product List App** is designed to help users manage a list of products, offering features such as adding, editing, and deleting items, while maintaining data consistency. It supports modern web technologies like React and Vite to provide a fast and responsive user experience. The app uses ESLint and Prettier for code quality and consistency.

---

## Installation

### Prerequisites

- **Node.js** version >= `14.x` (or the version required by your project)
- **npm** (Node Package Manager) or **yarn**

### Steps

1. Clone this repository:

   ```bash
   git clone https://github.com/mariontamnai/product-list.git
   ```

2. Navigate to the project directory:
   ```bash
   cd product-list
   ```

3. Install dependencies:
    ```bash
   npm install
   ```
4. If you don't have Husky and lint-staged installed, initialize them:
    ```bash
   npm run prepare
   ```
---

## Usage

### Running Locally

1. Start the development server:
   ```bash
   npm run dev
   ```
2. Open your browser and go to http://localhost:3000 to view the app.

### Code Formatting and Linting

- Prettier and ESLint are integrated into the project for code formatting and linting.
- Run Prettier to format the code:
   ```bash
   npm run format
   ```
- Run ESLint to check for code quality issues:
   ```bash
   npm run lint
   ```

### Git Hooks with Husky and lint-staged
- Husky is used to set up pre-commit and pre-push hooks.
- lint-staged ensures that only staged files are linted and formatted before committing.

---

## Contributing
We welcome contributions to the Product List App!

### How to Contribute
1. Fork this repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit them (git commit -am 'Add new feature').
4. Push to your fork (git push origin feature-branch).
5. Open a pull request to the main repository.

Please ensure that your code adheres to the existing style guidelines and that all tests pass before submitting a pull request.

---

## Acknowledgements
- Thanks to [React](https://reactjs.org/) and [Vite](https://vitejs.dev/) for providing excellent development tools.
- Prettier, ESLint, Husky, and lint-staged for enforcing code quality and consistency.
- Inspiration from [Frontend Mentor](https://www.frontendmentor.io/challenges) challenges

---


## Badges


### Key Sections:
- **Description**: Gives a brief overview of the project and its features.
- **Installation**: Lists the steps required to set up the project locally, including installing dependencies and running it.
- **Usage**: Explains how to run the project locally, and use code quality tools.
- **Contributing**: Guidelines for contributing to the project.
- **Acknowledgements**: Credits for tools, libraries, and resources used in the project.
- **Badges**: Adds visual indicators, such as build status and license.


