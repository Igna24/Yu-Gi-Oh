# Yu-Gi-Oh! Card Registry

## Description

This project provides a system for registering and searching Yu-Gi-Oh! trading cards. Users have the capability to add new cards, modify existing ones, remove cards, and conduct searches by card name or type. The interface displays the cards in a paginated format to simplify navigation.

## Created by

Ignacio Marín Garro

## Copyright

All rights reserved. The intellectual property of this work belongs exclusively to Ignacio Marín Garro. Unauthorized distribution or reproduction, partially or entirely, of this project is strictly forbidden without explicit permission from the author.

## Prerequisites

- Node.js and npm must be installed on your system to run the server.
- A MongoDB database must be accessible, with the `MONGODB_URI` variable in `server.js` set to the correct connection URL.

## Installation

1. Download the source code from the repository.
2. Execute the following command in the terminal to install server dependencies:
   - `npm install`

## Usage Instructions

1. Launch the server by entering:
   - `node server.js`
2. Open `http://localhost:3000` in a web browser to access the system.
3. Add a new card via the creation form on the home page.
4. To edit a card, select it from the created card list to bring up the edit form.
5. Remove a card using the "Delete" option within the edit form.
6. Perform card searches by typing into the search box and clicking "Search".
7. Filter the cards by type with the "Filter by Type" selection menu.
8. Navigate through the paginated card display by selecting page numbers at the bottom.

## Project Structure

- `server.js`: The main server file with Express routes for card management in the MongoDB database.
- `scripts.js`: A JavaScript file managing DOM interactions and AJAX requests for card operations.
- `index.html`: The primary system page, showing the new card form and the card list.
- `styles.css`: The style sheet for the website's design.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose (Object Data Modeling library)
- jQuery
- HTML5
- CSS3

## Additional Notes

- Verify a proper MongoDB database connection before starting the server to prevent database-related errors.
- This project is intended for educational uses and might need more tuning and enhancement for production deployment.

**Enjoy organizing your Yu-Gi-Oh! card collection!**
