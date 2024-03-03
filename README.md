**Github Favorites App**

## Overview

The Github Favorites project is a simple web application built in JavaScript that allows users to search for Github users and add them to their favorites list, the objective of this project was to improve and exercise fundamental concepts in JavaScript.

## JavaScript Concepts Applied

1. **Classes**: The application utilizes JavaScript classes to organize the code into logical components. Classes such as `Favorites` and `FavoritesView` encapsulate related functionality, making the code modular and easier to manage.

2. **Asynchronous Programming with Async/Await**: Asynchronous operations, such as fetching data from the Github API, are handled using `async/await` syntax. This allows for non-blocking code execution, ensuring a smooth user experience while waiting for API responses.

3. **LocalStorage**: The application employs `localStorage` to persist user data such as favorite Github users between sessions. This enables users to access their favorite users even after refreshing the page or closing the browser.

4. **Error Handling with Try/Catch**: Error handling is implemented using `try/catch` blocks to gracefully handle potential errors that may occur during user interactions, such as when searching for a non-existent Github user or attempting to add a user that is already in the favorites list.

5. **DOM Manipulation**: The application dynamically manipulates the DOM (Document Object Model) to update the user interface based on user interactions and data changes. Elements such as user profiles and remove buttons are created, modified, and removed from the DOM as needed.

6. **Event Handling**: Event listeners are used to respond to user actions such as clicking on buttons or inputting text. These event handlers trigger specific actions within the application, such as adding or removing users from the favorites list.

7. **Fetch API**: The Fetch API is utilized to make HTTP requests to the Github API and retrieve information about Github users. The `fetch()` function is used to asynchronously fetch data from the API, which is then processed and displayed to the user.

## Getting Started

To run the Github Favorites app locally, follow these steps:

1. Clone the repository to your local machine:
   ```
   git clone <repository_url>
   ```

2. Navigate to the project directory:
   ```
   cd github-favorites-app
   ```

3. Open the `index.html` file in your preferred web browser.

4. Start searching for your favorite Github users and add them to your favorites list!

**Acess Deploy**

[Link to the deployed application](https://patrickluizdev.github.io/GithubFavorites/)

## Dependencies

The Github Favorites app relies on the following dependencies:

- None

All necessary functionality is implemented using native JavaScript and browser APIs, requiring no external libraries or frameworks.