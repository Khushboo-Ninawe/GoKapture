# Spreadsheet App

This project is an interactive, responsive spreadsheet application built using Next.js,
Zustand for state management, and Tailwind CSS for styling. The application provides a grid of editable cells with support for features like data validation, undo/redo, and pagination.

# Features

Grid Rendering:- A 1000-cell grid that is efficiently rendered and easy to interact with.
Cell Editing:- Editable cells with dynamic content updates.
Data Storage:- Persistent state management using Zustand.
Responsive Design:- Grid and cells are responsive, styled with Tailwind CSS.
Cell Formatting:- Support for basic formatting like text alignment and font size adjustments.
Data Validation:- Basic validation rules (e.g., numeric-only cells).
Search and Filter:- Quickly locate specific data within the grid.
Undo/Redo:- Revert changes with undo and redo functionality.
Pagination:- Efficient handling of large datasets with pagination.

# Technologies Used

Next.js:- A React framework for server-side rendering and building static websites.
Zustand:- A small, fast, and scalable state management solution.
Tailwind CSS:- A utility-first CSS framework for custom designs without leaving your HTML.

# Installation

1. Repository:
bash
    git clone https://github.com/Khushboo-Ninawe/GoKapture.git


2. Install the dependencies:
npm install

3. Initialize Tailwind CSS:
 npx tailwindcss init -p
  

4. Start the server:
  npm run dev
   

5. for UI
    http://localhost:3000
 

# Project Structure

components:- Contains React components like `Cell.js` and `Grid.js`.
pages:- The main entry point for the application, typically `index.js` or `page.js`.
store:- Contains Zustand store for state management.
styles:- Global styles and Tailwind CSS configurations.
