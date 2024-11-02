# SportscastWeather

### Status: In Progress

![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)

## Table of Contents
1. [Description](#description)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
6. [License](#license)
7. [Contributing](#contributing)
8. [Tests](#tests)
9. [Questions](#questions)

## Description
Sportscast Weather is a fun weather forecast API that delivers a 5-day weather report in the energetic style of a sports announcer! Simply provide a city, and get a play-by-play breakdown of the weather, complete with temperatures, conditions, and wind speeds. Perfect for planning your next adventure!

## Features
- Retrieve a 5-day weather forecast for any city.
- Weather updates presented in a lively sports announcer style.
- Easy-to-use API for seamless integration into your applications.
- Supports multiple cities and retains search history.

## Installation
To use the application, follow these steps:

- Step 1: Clone the repository
- Step 2: Navigate to the project directory by typing cd slugfolio.
- Step 3: Once you're inside the folder, install the required dependencies by running npm install.

## Usage
To start the application, run the following command: `node server.js`.

API Endpoint
POST /forecast: Accepts a request body with a location and returns a 5-day weather forecast in the style of a sports announcer.

Example Request:
{
  "location": "Sacramento, CA"
}

Example Response:
{
  "result": {
    "day1": "And here we go, folks! Day one in Sacramento is looking like a scorcher with a high of 95 degrees and clear skies. It's going to be a hot one out there!",
    ...
  }
}

## License
This project is licensed under the MIT License, which allows you to freely use, modify, and distribute this software, provided proper attribution is given.

## Contributing
This project is part of a coding bootcamp assignment and is not open for contributions. To comply with the course requirements, I must complete this project individually without outside assistance. Therefore, pull requests, issues, or other contributions will not be accepted. Thank you for understanding!

## Tests
Currently, this project does not have any automated tests.

## Questions
If you have any questions about the repository, feel free to reach out by opening an issue or contacting me directly at cheyennaraelynn@gmail.com You can also find more of my work on GitHub at https://github.com/RaeOfChey.
