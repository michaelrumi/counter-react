# Counter Application using Redux in React

This is a basic counter application developed using Redux and React. It demonstrates how to use Redux for state management in a React application.

The application consists of a single `MyButton` component which maintains a counter value. On every click of the `MyButton`, the counter value increments. The updated counter value is then displayed on a `DivPanel` component.

## Structure

The application is structured into three main parts:

- Actions: Defines the actions that can be performed on the counter value. In this case, the only action available is to increment the counter.

- Reducers: Defines how the actions modify the state of the application. In this application, the reducer increases the counter value when the 'increment' action is dispatched.

- Components: Includes `MyButton` and `DivPanel` components. `MyButton` is responsible for incrementing the counter value, and `DivPanel` is responsible for displaying the updated counter value.

## Setup

To set up and run this project locally:

1. Clone this repository
2. Navigate to the project directory
3. Install the required npm packages using `npm install`
4. Start the server using `npm start`

## Author
MichaelRumi

## License
This project is licensed under the MIT License - see the LICENSE file for details
