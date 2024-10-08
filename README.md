﻿### Guestara Assignment

## Description

This is a RESTful API built with Node.js and Express to manage a restaurant's menu, including items, categories, and subcategories. It provides endpoints to:

- **Menu:** Create, retrieve, update menus.
- **Submenu:** Create, retrieve, update submenus associated with a menu.
- **Item:** Create, retrieve, update associated with either a menu or a submenu.

## Technologies Used

- Node.js
- Express.js
- MongoDB (Database)
- Mongoose (ORM)
- [Other: body-parser, multer, etc.]

## Installation and Setup

1. **Clone the repository:**
   git clone https://github.com/the-gaurav-bhatt/Menu-Management
   cd
2. **Install dependencies:**
   npm install
3. **Set up environment variables:**
   - Create a `.env` file in the root directory.
   - Add the following environment variables and replace the placeholders with your actual values:
     PORT=3000
     URI=<your-mongodb-connection-string>
4. **Start the server:**
   nodemon src/server.ts
