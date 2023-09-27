# Birthday Reminder Project

![Project Image](https://ibb.co/p2Nr8pW)

This project is a simple React application that displays a list of people with their names, ages, and images. Users can clear the list of birthdays displayed. The project is designed to help users keep track of upcoming birthdays.

## Technologies Used

- React
- useState hook
- JSX
- CSS

## Project Structure

- `App.js`: The main component that manages the state of the list of people and renders the list and clear button.
- `List.js`: A functional component that receives the list of people as a prop and renders each person's information.

## How to Use

1. Clone the repository to your local machine.
2. Install the necessary dependencies using `npm install`.
3. Start the application using `npm start`.
4. The list of birthdays will be displayed, and you can click the "clear all" button to remove them.

## Project Outcome

This project demonstrates the following concepts and techniques:

1. **React Components**: It uses React components to create a modular and reusable structure for building the user interface.

2. **State Management**: The `useState` hook is used to manage the state of the list of people. This allows for dynamic updates to the UI.

3. **Mapping Data**: The project showcases how to map through an array of data and render individual items using the `map` function.

4. **Handling Events**: It demonstrates how to handle user interactions by using event handlers, such as the `onClick` event for the "clear all" button.

5. **Component Communication**: The `List` component receives data from its parent component (`App`) through props, showcasing how components can communicate in a React application.

## Future Improvements

- Add a feature to dynamically add new birthdays.
- Implement sorting and filtering options for the list.
- Improve the styling and overall user experience.

Feel free to contribute to the project and make enhancements or modifications as needed. Happy coding!
