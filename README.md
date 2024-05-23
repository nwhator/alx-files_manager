# 0x04. Files Manager

## Overview

This project is a comprehensive summary of back-end technologies covered in the trimester, focusing on authentication, NodeJS, MongoDB, Redis, pagination, and background processing. The objective is to build a simple platform that allows users to upload and view files.

### Features

- User authentication via a token
- List all files
- Upload a new file
- Change permission of a file
- View a file
- Generate thumbnails for images

## Learning Objectives

By the end of this project, you should be able to explain:

- How to create an API with Express
- How to authenticate a user
- How to store data in MongoDB
- How to store temporary data in Redis
- How to set up and use a background worker

## Resources

Read or watch the following resources for guidance:

- Node JS getting started
- Process API doc
- Express getting started
- Mocha documentation
- Nodemon documentation
- MongoDB
- Bull
- Image thumbnail
- Mime-Types
- Redis

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`, `Visual Studio Code`
- All files will be interpreted/compiled on Ubuntu 18.04 LTS using node (version 12.x.x)
- All files should end with a new line
- A `README.md` file at the root of the project folder is mandatory
- Use the `.js` extension for your code
- Code will be verified against lint using ESLint

## Provided Files

Ensure you run `$ npm install` after receiving the provided `package.json`.

### package.json
```json
{
  // Your package.json content here
}
```

### .eslintrc.js
```js
module.exports = {
  // Your .eslintrc.js content here
}
```

### babel.config.js
```js
module.exports = {
  // Your babel.config.js content here
}
```

## Project Instructions

You will be guided step by step to build the platform, but you have the freedom to implement it in your own way, possibly splitting the code into more files (the `utils` folder can be very useful).

This project aims to help you understand and integrate each piece of technology to build a full product, similar to real-life services.

## Installation

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install all dependencies.

## Usage

1. Start the server using `npm start` or `nodemon`.
2. Use the provided endpoints to interact with the file management system.

Enjoy building your file manager!
