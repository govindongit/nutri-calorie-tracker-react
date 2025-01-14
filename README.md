# Nutrition and Calorie Tracker - React

## Main Concepts Used in the Code:

### 1. React Fundamentals

- **Functional Component**: The component is built as a functional component.
- **JSX Syntax**: The UI is created using JSX syntax, combining HTML-like elements with JavaScript functionality.
- **React Hooks**:
  - `useState`: For managing state in the component.
  - `useEffect`: To handle side effects like recalculating total calories when the list of items changes.

### 2. State Management

- **Managing State with `useState`**: State variables such as `nutritionItems`, `newItem`, and `totalCalories` are managed using the `useState` hook.
- **Handling Multiple State Variables**: Different state variables are used for managing nutrition items, user inputs, and total nutritional values.

### 3. Form Handling

- **Controlled Inputs**: Form elements are controlled by React state, binding inputs to state variables.
- **Form Validation**: Input fields are validated to ensure correct values are entered (e.g., non-negative values).
- **Add and Update Item Logic**: The logic for adding new items and updating existing ones based on user input.

### 4. Dynamic Rendering

- **Rendering a List of Items with `.map()`**: The nutrition items are displayed dynamically using the `.map()` function.
- **Conditional Rendering for Editing and Adding Items**: Based on whether an item is being edited, the "Add Item" button switches to "Update Item".

### 5. Event Handling

- **Handling Button Clicks**: Events such as adding, editing, deleting items, and adjusting quantities are handled through button clicks.
- **Form Input Changes**: Form fields update state variables as the user types, using the `onChange` event handler.

### 6. Total Nutrition Calculation

- **Calculating Totals (Calories, Protein, Carbs, Fat)**: The totals for calories, protein, carbs, and fat are calculated dynamically.
- **Using `reduce()` for Aggregation**: The `reduce()` function is used to sum up the values based on the quantity of each item.

### 7. Styling and Layout

- **Tailwind CSS for Utility-Based Styling**: The layout and styling are done using Tailwind CSS classes, enabling a responsive and customizable UI.
- **Responsive Grid Layout**: The grid layout is responsive, using Tailwind classes like `grid`, `gap-4`, `sm:grid-cols-2`, and others.
- **Conditional Styling**: Error states are styled with conditional CSS classes, such as red borders for invalid input fields.

### 8. FontAwesome Icons

- **Using FontAwesome Icons in React**: Icons such as `faEdit`, `faTrashAlt`, `faPlus`, and `faUtensils` are used in buttons and other UI elements to enhance the user experience.

### 9. Input Error Handling

- **Dynamic Input Validation**: Inputs are dynamically validated and styled with error indicators (e.g., red border when invalid data is entered).

### 10. Warning Messages

- **Displaying Warnings**: A warning message is displayed when the total calories exceed the recommended threshold (1000 calories).

### 11. Helper Functions

- **Functions for Total Calculation**: Functions like `totalCalories`, `totalProtein`, `totalCarbs`, and `totalFat` calculate the nutritional totals.
- **Helper Functions to Modify Item Quantity**: Functions like `updateItemQuantity` are used to increase or decrease the quantity of items in the list.

### 12. Conditional Actions

- **Differentiating Between Add and Update Actions**: The UI switches between the "Add Item" and "Update Item" actions based on whether an item is being added or edited.
- **Switching Button Labels Based on Edit Mode**: The label of the button changes to reflect whether the user is adding or editing an item.

![image](https://github.com/user-attachments/assets/19ab8623-8b84-401f-a340-9e0bbd57cfc3)

---

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
