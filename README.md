# NPM (Node Package Manager)

NPM is a package manager for JavaScript, primarily used to manage the dependencies of Node.js projects. It is included with Node.js installation and helps developers share, reuse code, manage dependencies, and automate development tasks.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
  - [Initializing a Project](#initializing-a-project)
  - [Installing Packages](#installing-packages)
  - [Global vs Local Installation](#global-vs-local-installation)
  - [Uninstalling Packages](#uninstalling-packages)
  - [Updating Packages](#updating-packages)
  - [Listing Installed Packages](#listing-installed-packages)
  - [Running Scripts](#running-scripts)
- [Package Management](#package-management)
  - [package.json](#packagejson)
  - [package-lock.json](#package-lockjson)
  - [Semantic Versioning](#semantic-versioning)
- [Publishing Packages](#publishing-packages)
- [Best Practices](#best-practices)
- [Resources](#resources)

## Installation

NPM is bundled with Node.js. To use it, you must install Node.js.

### Installing Node.js and NPM

1. **Download Node.js**: Visit the [Node.js website](https://nodejs.org/) and download the installer for your OS.
2. **Run the Installer**: Follow the installer instructions, which will also install NPM.
3. **Verify Installation**: Open your terminal and run:

   ```bash
   node -v
   npm -v
   ```
