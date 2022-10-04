# Back Alley Shop

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This application will allow the user to manage the backend portion of their online store through internal APIs.

## Table of Contents

- [Human Asset Tracker](#back-alley-shop)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Questions](#questions)
  - [License](#license)

## Installation

Download the files. Open a bash terminal in the main directory. Run "npm install". You will need mySQL installed and the connection details will need to be updated in the "index.js" file according to your database.

## Usage

Run "node index.js" or "npm start". Routes may be accessed through any compatible application. For testing, a program such as Insomnia will provide assurance of a functional API.

You may view categories, products, and tags through the provided Get routes. Adding an id parameter onto these Get routes will return the requested item. Post routes may be used to add new categories, products, and tags. Put routes are available for updating categories, products, or tags. Finally, Delete routes are available for removing any of the aforementioned. In regards to deletion, a a category cannot be deleted if it currently contains products.

[Video Link of Usage]([https://drive.google.com/file/d/1x4Gf5DlQOY4okppMlyFFFLgsNuLeLjIk/view](https://drive.google.com/file/d/1HtGyNsmsxeAB_ruApYgO2_37Ez9nJXiP/view))


[WebStoreAPI2x.webm](https://user-images.githubusercontent.com/35825121/193735916-a9211592-942f-450c-b2d1-0eaaa1d58798.webm)



## Questions

Github Profile: [acotterson](https://github.com/acotterson)

If you have any additional questions, I can be reached at [acotterson@gmail.com](mailto:acotterson@gmail.com).

## License

Licensed under the MIT License: [MIT](https://opensource.org/licenses/MIT)
