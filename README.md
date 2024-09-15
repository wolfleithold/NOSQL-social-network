# NOSQL Social Network

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

1. [Description](#description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)
6. [Questions](#questions)
7. [Tutorial-Video](#tutorial)

## Description

This project is a NoSQL application built with MongoDB and Node.js. It includes a RESTful API for managing thoughts and reactions. Users can create, read, update, and delete thoughts. Each thought can have reactions, and these reactions can also be managed through the API. The application demonstrates the use of MongoDB for NoSQL data storage and Express.js for handling API routes.

## Installation

Requires express and mongodb.

## Usage

- Create a Thought: POST /api/thoughts
- Get All Thoughts: GET /api/thoughts
- Get a Single Thought: GET /api/thoughts/:thoughtId
- Update a Thought: PUT /api/thoughts/:thoughtId
- Delete a Thought: DELETE /api/thoughts/:thoughtId
- Add a Reaction: POST /api/thoughts/:thoughtId/reactions
- Delete a Reaction: DELETE /api/thoughts/:thoughtId/reactions/:reactionId

## Contributing

Contribution Guidelines

- Code of Conduct: Please adhere to our Code of Conduct in all your interactions with the project.
- Testing: Ensure that your changes do not break any existing functionality and include tests if applicable.
- Documentation: Update the documentation (including the README file) as necessary to reflect your changes.
  Thank you for contributing!

## License

This project is licensed under the MIT License. See the [MIT License](https://opensource.org/licenses/MIT) for details.

## Questions

For any questions, please contact me at [wolfleithold@gmail.com](mailto:wolfleithold@gmail.com).
You can also find me on GitHub: [wolfleithold](https://github.com/wolfleithold).

## Tutorial

[Video-tutorial](https://drive.google.com/file/d/1vbeTglQa4R4SSrjraArl5QlRddn7GtW5/view)
