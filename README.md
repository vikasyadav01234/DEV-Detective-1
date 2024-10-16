# DevDetective README
=====================

## Project Description
Dev Detective is a web application designed to fetch and display GitHub user profiles using the GitHub API. This project aims to provide a simple and intuitive interface for users to search for any GitHub username and view detailed information about the user’s profile.

## Features
* **User Search**: Enter a GitHub username to retrieve the user’s profile information.
* **Profile Display**: View the user’s profile picture, name, bio, location, number of followers, number of following, and public repositories.
* **Repository List**: Display a list of the user’s public repositories with links to each repository.
* **Responsive Design**: Ensure the application is accessible and user-friendly on various devices.

## Technologies Used
* **Frontend**: HTML, CSS, JavaScript
* **API**: GitHub REST API

## Implementation Steps

### Setup Project

* Initialize a new project directory.
* Create the necessary HTML, CSS, and JavaScript files.

### Fetch GitHub User Data

* Use Axios to make GET requests to the GitHub API endpoint for user data.
* Handle the API response to extract relevant user information.

### Display User Profile

* Dynamically update the HTML to display the fetched user profile information.
* Include error handling for invalid usernames or API request failures.

### Styling

* Use Bootstrap to create a responsive and visually appealing layout.
* Customize the design to enhance user experience.

### Testing

* Test the application with various GitHub usernames to ensure accurate data retrieval and display.
* Ensure the application works smoothly across different browsers and devices.

## How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/vikasyadav01234/DEV-Detective-1

cd DEV-Detective-1

Open index.html in your preferred web browser.