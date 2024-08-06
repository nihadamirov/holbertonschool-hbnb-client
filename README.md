# HBnB Evolution Project: Part 3 - Front-end Web Development

## Overview
In this phase of the HBnB Evolution Project, we focus on developing the front-end of our application using HTML5, CSS3, and JavaScript ES6. The goal is to create an interactive and user-friendly interface that communicates seamlessly with our back-end services.

## Objectives
- Develop a user-friendly interface following provided design specifications.
- Implement client-side functionality to interact with the back-end API.
- Ensure secure and efficient data handling using JavaScript.
- Apply modern web development practices to create a dynamic web application.

## Learning Goals
- Understand and apply HTML5, CSS3, and JavaScript ES6 in a real-world project.
- Learn to interact with back-end services using AJAX/Fetch API.
- Implement authentication mechanisms and manage user sessions.
- Use client-side scripting to enhance user experience without page reloads.

## Tasks Breakdown

### Design (Task 1)
- Complete the provided HTML and CSS files to match the given design specifications.
- Create pages for Login, List of Places, Place Details, and Add Review.

### Login (Task 2)
- Implement login functionality using the back-end API.
- Store the JWT token returned by the API in a cookie for session management.

### List of Places (Task 3)
- Implement the main page to display a list of all places.
- Fetch places data from the API and implement client-side filtering based on country selection.
- Ensure the page redirects to the login page if the user is not authenticated.

### Place Details (Task 4)
- Implement the detailed view of a place.
- Fetch place details from the API using the place ID.
- Provide access to the add review form if the user is authenticated.

### Add Review (Task 5)
- Implement the form to add a review for a place.
- Ensure the form is accessible only to authenticated users, redirecting others to the index page.

## Resources
- [HTML5 Documentation](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
- [CSS3 Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
- [JavaScript ES6 Features](https://developer.mozilla.org/en-US/docs/Web/JavaScript/New_in_JavaScript/ECMAScript_6_support_in_Mozilla)
- [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- [Handling Cookies in JavaScript](https://developer.mozilla.org/en-US/docs/Web/API/Document/cookie)
- [Client-Side Form Validation](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)
- [Mock API for Testing](https://jsonplaceholder.typicode.com/)

## Getting Started
1. Clone the repository:
    ```bash
    git clone https://github.com/nihadamirov/holbertonschool-hbnb-client.git
    cd holbertonschool-hbnb-client
    ```

2. Open the `index.html` file in your preferred web browser to start the application.

## Usage

### Login Page
1. Open the `login.html` file.
2. Enter your credentials and submit the form.
3. The JWT token will be stored in a cookie for session management.

### List of Places Page
1. Open the `places.html` file.
2. The list of places will be fetched from the API.
3. Use the country filter to narrow down the results.

### Place Details Page
1. Open the `place-details.html` file.
2. The details of the selected place will be fetched from the API.

### Add Review Page
1. Open the `add-review.html` file.
2. Ensure you are logged in to access the form.
3. Submit your review for the selected place.

## Contributing
We welcome contributions to this project! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgments
- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
- [JavaScript ES6](https://developer.mozilla.org/en-US/docs/Web/JavaScript/New_in_JavaScript/ECMAScript_6_support_in_Mozilla)
- [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- [Mock API for Testing](https://jsonplaceholder.typicode.com/)
```
