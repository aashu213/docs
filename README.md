## ✈️ Getting started

### Prerequisites

1.  [Git](https://git-scm.com/downloads).
1.  [Node](https://nodejs.org/en/download/) _(version 12 or greater)_.
1.  [Yarn](https://yarnpkg.com/lang/en/docs/install/) _(version 1.5 or greater)_.
1.  A fork of the repo _(for any contributions)_.
1.  A clone of the `react-native-website` repo.

### Installation

1.  `cd react-native-website` to go into the project root.
1.  Run `yarn` to install the website's workspace dependencies.

### Running locally

1.  `cd website` to go into the website portion of the project.
1.  `yarn start` to start the development server _(powered by [Docusaurus](https://v2.docusaurus.io))_.
1.  `open http://localhost:3000/` to open the site in your favorite browser.

## 📖 Overview

If you would like to **_contribute an edit or addition to the docs,_** read through our [style guide](STYLEGUIDE.md) before you write anything. 
Almost all our content is generated from markdown files you can find in the `docs`, `website/architecure` and `website/contibuting` directories.

**_To edit the internals of how the site is built,_** you may want to get familiarized with how the site is built. The React Native website is a static site generated using [Docusaurus](https://docusaurus.io/). 
The website configuration can be found in the `website` directory. Visit the Docusaurus website to learn more about all the available configuration options.


## 🔧 Website configuration

The main config file for the website can be found at `website/docusaurus.config.js`. This file tells [Docusaurus how to build the website](https://v2.docusaurus.io/docs/configuration). Edits to this file are rarely necessary.

The `core` subdirectory contains JavaScript and React components that are the core part of the website.

The `src/pages` subdirectory contains the React components that make up the non-documentation pages of the site, such as the homepage.

The `src/theme` subdirectory contains the swizzled React components from the Docusaurus theme.

The `showcase.json` file contains the list of users that are highlighted in the React Native showcase.

## 👏 Contributing

