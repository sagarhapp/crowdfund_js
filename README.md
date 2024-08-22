# Project-Crowdfunding

Project-Crowdfunding is a decentralized application (dApp) built on the Ethereum blockchain to facilitate crowdfunding campaigns. Users can create, fund, and manage campaigns in a secure and transparent manner, leveraging blockchain technology.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Smart Contracts](#smart-contracts)
- [License](#license)

## Project Structure

The project is divided into several key directories:

### Client

This directory contains the frontend code of the application, developed using React and Vite.js.

- **src**: Contains the source code for the frontend.
  - **App.jsx**: The main component that wraps the entire application.
  - **components**: Houses reusable components such as `Navbar`, `Sidebar`, `CustomButton`, and more.
  - **context**: Contains the global context to manage application state.
  - **pages**: Contains the main pages of the application like `Home`, `CampaignDetails`, `Profile`, etc.
  - **assets**: Static assets like images, icons, etc.
  - **constants**: Contains constant values and configurations.
  - **utils**: Utility functions used across the project.
  - **index.css**: Global CSS styles for the application.
  - **main.jsx**: The entry point for the React application.
- **index.html**: The main HTML file.
- **vite.config.js**: Vite.js configuration file.
- **tailwind.config.js**: Tailwind CSS configuration file.
- **package.json**: Contains project dependencies and scripts.
- **yarn.lock** / **package-lock.json**: Lock files to ensure consistent installs.

### Web3

This directory contains the blockchain-related code, including smart contracts and configurations.

- **contracts**: Solidity smart contracts that define the core logic for the crowdfunding platform.
- **hardhat.config.js**: Configuration for Hardhat, a development environment for Ethereum.
- **package.json**: Contains dependencies related to Ethereum and Hardhat.
- **node_modules**: Installed dependencies.
- **yarn.lock** / **package-lock.json**: Lock files for dependency management.

## Installation

To get started with the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/sagarhapp/project-crowdfunding.git

2. Navigate to the client directory and install dependencies:
    ```cd client
    yarn install


## Running the Frontend:

Navigate to the `client` directory and start the development server:

```bash
cd client
yarn dev






