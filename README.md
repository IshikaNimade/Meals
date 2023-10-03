# React Native Expense Tracker App

<img src='meals.gif' width='300'  alt='App Screen'>

## Description

The Meals app is a mobile application that helps users discover and manage their favorite meal recipes. 
It uses React Native with Stack Navigation and Drawer Navigation for a smooth user experience. 
The app leverages both Redux and Context API for efficient state management.

## Features

- **All Categories**: On the starting screen, you'll find a list of all meal categories. Clicking on a category navigates to the "Meals Overview" page.

- **Meals Overview**: Here, you can explore a list of meals specific to the selected category. Clicking on a meal navigates to the "Meal Detail" page.

- **Meal Detail**: This page provides detailed information about a meal, including ingredients and steps to make the meal. It also features a star button on the header to mark the meal as a favorite.

- **Favorites**: Access the "Favorites" screen via the drawer navigation to view all your favorite meals. Meals can be marked as favorites from the "Meal Detail" screen.


## Installation

1. Clone the repository:
   ```bash
   git clone git remote add origin https://github.com/IshikaNimade/Meals.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Meals
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

   Or with yarn:
   ```bash
   yarn install
   ```

5. Start the application:
   - For Android:
     ```bash
     npx react-native run-android
     ```
   - For iOS:
     ```bash
     npx react-native run-ios
     ```

## Navigation

- **Stack Navigation**: Used for navigating between the "All Categories," "Meals Overview," and "Meal Detail" screens.
- **Drawer Navigation**: Provides access to the "All Categories" and "Favorites" screens from any part of the app.

## State Management

- **Redux**: Utilized for global state management, allowing efficient handling of app-wide data.
- **Context API**: Used for managing specific local state, such as UI components and interactions.

## Usage

The Meals app is designed to be user-friendly and intuitive. Follow these steps to use the app effectively:

1. **Starting Screen**:
   - When you launch the app, you'll land on the starting screen, which displays a list of all meal categories.

2. **Exploring Categories**:
   - Click on any category to navigate to the "Meals Overview" page for that specific category.

3. **Meals Overview**:
   - On the "Meals Overview" page, you'll see a list of meals associated with the selected category.
   - Click on any meal to view its details on the "Meal Detail" page.

4. **Meal Detail**:
   - The "Meal Detail" page provides comprehensive information about the meal, including ingredients and steps to prepare it.
   - To mark a meal as a favorite, click the star button located in the header.

5. **Drawer Navigation**:
   - Access the drawer navigation by swiping from the left edge of the screen or clicking the menu icon in the header.
   - The drawer navigation provides two main options: "All Categories" and "Favorites."

6. **All Categories**:
   - Select "All Categories" from the drawer to return to the list of all meal categories.
   - Explore different categories and meals by repeating the previous steps.

7. **Favorites**:
   - Select "Favorites" from the drawer to view a list of your favorite meals.
   - Meals can be marked as favorites from the "Meal Detail" page by clicking the star button.

8. **Managing Favorites**:
   - To remove a meal from your favorites, simply click the star button again on the "Meal Detail" page.
   - Your changes will be reflected in the "Favorites" section.

9. **Redux and Context API**:
   - The app utilizes Redux for managing global state, including favorites.
   - Context API is used for handling specific local state and UI interactions.

10. **Enjoy Exploring and Cooking!**:
    - Use the Meals app to discover new recipes, organize your favorite meals, and enjoy cooking delicious dishes.

Feel free to explore the app, mark your favorite meals, and use the navigation features to switch between different screens seamlessly. The app aims to make your meal planning and cooking experience enjoyable and hassle-free.


## Dependencies

Here are the major libraries and dependencies used in this project:

- [React Native](https://reactnative.dev/docs/getting-started)
- [React Navigation](https://reactnavigation.org/docs/getting-started)
- [React Navigation Drawer](https://reactnavigation.org/docs/drawer-navigator/)
- [React Navigation Native Stack](https://reactnavigation.org/docs/native-stack-navigator/)
- [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)
- [Redux](https://redux.js.org/introduction/getting-started)
- [React Redux](https://react-redux.js.org/introduction/getting-started)
- [Redux Toolkit](https://redux-toolkit.js.org/introduction/getting-started)

Please refer to the official documentation for each library to learn more about their usage and configurations.


## Contributions

Contributions to the project are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature.
3. Implement your changes.
4. Open a pull request detailing your changes.

## Contact

For any inquiries or support, please contact [ishikanimade56@gmail.com](mailto:ishikanimade56@gmail.com).

Feel free to customize the sections and content as per your specific application requirements and reach out to us with any questions, feedback, or suggestions you may have.













