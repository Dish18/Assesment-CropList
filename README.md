# Crop List Web Application

## Screen 1 - Login Page:

- **Technology Used:** React for building the user interface.
- **Components:**
  - `Login.js`: Manages the login page with input fields for username and password.
  - `App.js`: The main application component that handles routing.
- **Authentication:**
  - Default credentials: Username - `bharatagri`, Password - `1234`.
  - Displays relevant error messages on incorrect credentials.

## Screen 2 - Crop List:

- **Technology Used:** React, Axios for API requests, and ReactPaginate for pagination.
- **Components:**
  - `CropList.js`: Renders the list of crops from API 1 in a responsive grid layout.
  - `App.js`: Manages the routing between login and crop list screens.
- **API Interaction:**
  - Uses Axios to fetch data from [API](https://api-cache-test.leanagri.com/pop/pop_list/en/64/pop_list.json).
- **Responsive Grid Layout:**
  - Crop information displayed in separate cards.
  - Auto-fit sized crop images centered in each card.
  - 2 or 3 crop cards displayed in a row based on screen size.
- **Modal:**
  - Modal opens on clicking a crop card, displaying the crop image alone.

## Brownie Points - Pagination:

- **Technology Used:** ReactPaginate library.
- **Pagination Implementation:**
  - Displays 10 crops per page.
  - Navigation between pages using pagination controls.

## Search Functionality:

- Added search functionality to filter crops based on the crop name.
- Users can enter a search term to dynamically filter and display relevant crops.
- A "Reset" button allows users to clear the search and display the full list of crops.

## Tech Notes:

- **State Management:** Utilizes React hooks for managing state (useState, useEffect).
- **Routing:** React Router (BrowserRouter) for navigation between login and crop list screens.
- **Styling:** CSS (app.css) for basic styling, responsiveness, and modal appearance.
- **API Requests:** Axios library for fetching data from the provided API.
- **Pagination:** ReactPaginate library for paginating the crop list.
- **Code Structure:** Modular components for maintainability and readability.
