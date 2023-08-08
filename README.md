# Shopify Template Readme

[![NodeJS](https://img.shields.io/badge/NodeJS-16%2B-brightgreen)](https://nodejs.org/)
[![Ruby+Devkit](https://img.shields.io/badge/Ruby%2BDevkit-3.0-blue)](https://rubyinstaller.org/)

This repository contains a Shopify template designed to help you get started with your Shopify theme development. It leverages NodeJS, Ruby+Devkit, and git for the development environment. Follow the instructions below to set up and utilize this template effectively.

## Requirements

Before using this Shopify template, make sure you have the following software installed on your system:

- **NodeJS 16 or higher**: NodeJS is required for managing dependencies and running the development server.
- **Ruby+Devkit 3.0**: Ruby and the Devkit are essential for working with certain Ruby gems required by the Shopify theme.
- **Git**: Git is necessary for version control and managing the repository.

## Global Installations

After meeting the requirements above, ensure that you have the following packages installed globally:

```bash
npm install -g @shopify/cli
npm install -g @shopify/theme
```

## Theme Initialization

To set up the Shopify theme, run the following command:

```bash
shopify theme init {repo URL}
```

Replace `{repo URL}` with the URL of this repository (`https://github.com/Peallyz/shopify_template.git`).

## Development and Preview

To start the development server and preview your theme, execute the following command:

```bash
shopify theme dev --store {store-name}
```

Replace `{store-name}` with the name of your Shopify store. The development server will be accessible at `http://127.0.0.1:9292`, where you can preview and test your Shopify theme in real-time.

## Using Sass with Gulp

This template supports the use of Sass through the Gulp task runner. You can compile your Sass files using the following command:

```bash
gulp sass
```

Additionally, to watch for changes in your Sass files and automatically trigger compilation, use the following command:

```bash
gulp watch
```

## License

This Shopify template is licensed under the MIT License, allowing you to modify and use it freely. For more details, see the [LICENSE](LICENSE) file.

## Contribution

We appreciate your interest, but this repository does not have a specific contribution section. If you encounter any issues or have suggestions, feel free to create an issue or fork the repository.

Happy Shopify theme development! 🚀