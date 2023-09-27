# Tours Website Project

<img src="https://i.ibb.co/hHvshn4/Screenshot-2023-09-27-at-15-27-38.png" alt="Screenshot-2023-09-27-at-15-27-38" border="0">
<img src="https://i.ibb.co/Krgp0rv/Screenshot-2023-09-27-at-15-27-55.png" alt="Screenshot-2023-09-27-at-15-27-55" border="0">
<img src="https://i.ibb.co/CBPZLh7/Screenshot-2023-09-27-at-15-28-05.png" alt="Screenshot-2023-09-27-at-15-28-05" border="0">
This project is a simple React application that displays a list of tours. Users can view tour details, read more information, and remove tours they are not interested in. The tours are fetched from an API.

## Technologies Used

- React
- useState hook
- useEffect hook
- Fetch API
- CSS

## Project Structure

- `App.js`: The main component that manages the state of tours, fetches data from an API, and handles tour removal.
- `Tours.js`: A functional component that displays the list of tours and the "Read More" functionality.
- `Tour.js`: A functional component that displays individual tour details and handles removal.

## How to Use

1. Clone the repository to your local machine.
2. Install the necessary dependencies using `npm install`.
3. Start the application using `npm start`.
4. The list of tours will be displayed, and you can click the "Read More" button to view more details. You can also click the "Not Interested" button to remove a tour.

## Project Outcome

This project demonstrates the following concepts and techniques:

1. **React Components**: It uses React components to create a modular and reusable structure for building the user interface.

2. **State Management**: The `useState` hook is used to manage the state of tours, and the `useEffect` hook is used to fetch data from an API.

3. **Fetching Data**: Data is fetched from the "https://course-api.com/react-tours-project" API using the Fetch API.

4. **Conditional Rendering**: The "Read More" functionality is implemented with conditional rendering, showing a shortened description by default and the full description when the user clicks the button.

5. **Handling Events**: The project demonstrates how to handle user interactions, such as clicking the "Not Interested" button to remove a tour.

## Future Improvements

- Add more features, such as sorting and filtering tours.
- Improve the user interface and styling for a better user experience.
- Implement user authentication and the ability to save favorite tours.

Feel free to contribute to the project and make enhancements or modifications as needed. Happy coding!
