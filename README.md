# Crop List Web Application

# Live-Link

Visit the live application at [assesment-croplist.netlify.app](https://assesment-croplist.netlify.app).

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

- # Installation Requirements

## Node.js and npm:

### Installation:
1. Download and install Node.js from [nodejs.org](https://nodejs.org/).
2. npm (Node Package Manager) is included with Node.js.

## Create React App:

### Installation:
1. Open a terminal or command prompt.
2. Run the following command to install Create React App globally:
    ```bash
    npm install -g create-react-app
    ```
3. Create a new React app:
    ```bash
    npx create-react-app crop-list-app
    ```
4. Change into the app's directory:
    ```bash
    cd crop-list-app
    ```

## React Router:

### Installation:
1. Inside the project directory, run the following command to install React Router:
    ```bash
    npm install react-router-dom
    ```

## Axios:

### Installation:
1. Run the following command to install Axios for handling API requests:
    ```bash
    npm install axios
    ```

## ReactPaginate:

### Installation:
1. Run the following command to install ReactPaginate for pagination:
    ```bash
    npm install react-paginate
    ```

## Bootstrap (Optional - for Styling):

### Installation:
1. Run the following command to install Bootstrap:
    ```bash
    npm install bootstrap
    ```
   
### Integration:
1. Import Bootstrap in your index.js file:
    ```jsx
    import 'bootstrap/dist/css/bootstrap.min.css';
    ```

## Modal Styles (Optional):

### Installation:
1. If custom modal styles are used, ensure that the necessary CSS is included or linked in your project.

# Run the Application

1. After installing the required packages, start the development server:
    ```bash
    npm start
    ```
2. Open your browser and visit [http://localhost:3000](http://localhost:3000) to view the application.

