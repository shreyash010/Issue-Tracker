# Issue Tracker Web Application
[Deployed on Render](https://issue-tracker-010.onrender.com)

This is a simple web application that allows users to create and track issues. This code is written using Node.js, Express, and MongoDB.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine
2. Install the required dependencies using `npm install`
3. Start the server using `npm start`

## Usage

Once the server is up and running, you can access the web application by visiting `http://localhost:8000`.

### Create a new issue

To create a new issue, click on the "New Issue" button on the homepage. Fill out the form with the necessary information and click "Submit". The new issue will be added to the list of existing issues.

### View existing issues

On the homepage, you can see a list of all existing issues. Each issue includes its name, author, and description. You can click on the "Open project" button to view more details about the issue.

## Code Structure

The code for this project is structured as follows:

- `app.js` - This is the main file that initializes the Express app and sets up the routes.
- `models/issue.js` - This file defines the Issue schema for MongoDB.
- `routes/index.js` - This file defines the routes for the web application.
- `views/` - This directory contains the EJS templates used to render the HTML pages.

## Contributing

If you would like to contribute to this project, feel free to submit a pull request. Please make sure to follow the existing code style and include tests for any new features or bug fixes.
