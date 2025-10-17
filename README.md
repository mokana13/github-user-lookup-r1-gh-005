# github-user-lookup

## Summary
This project was automatically generated to fulfill the following requirement:

Publish a Bootstrap page with a form. The form should have a text input for a GitHub username and a submit button. When submitted, it should fetch user data from the GitHub API (https://api.github.com/users/USERNAME) and display the account creation date (created_at field) in 'YYYY-MM-DD' format inside an element with the id '#creation-date'.

## Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/<username>/github-user-lookup.git
   cd github-user-lookup
   ```
2. Open `index.html` in a web browser, or deploy via GitHub Pages

## Usage
- Open the deployed GitHub Pages URL or open `index.html` locally
- The application will automatically load and execute according to the brief requirements

## Evaluation Criteria
This application is evaluated against the following checks:
- Page contains a form element.
- The generated JavaScript makes a fetch request to api.github.com.

## Code Explanation
The application is built as a single-page HTML file (`index.html`) that includes:
- **HTML Structure**: Semantic markup with proper accessibility attributes
- **CSS Styling**: Utilizes Bootstrap 5 for responsive design
- **JavaScript Logic**: Handles the core functionality as specified in the brief
- All dependencies are loaded from CDNs for easy deployment

The code was generated using AI assistance based on the project brief and automatically deployed to GitHub.

## License
MIT License - See LICENSE file for details


---

## Round 2 Update

**Brief**: Show an aria-live alert element with the id '#github-status' that reports when a lookup starts ('Loading...'), succeeds ('User found!'), or fails ('User not found.').

**New Evaluation Criteria**:
- An element with id '#github-status' exists.
- The status text changes on successful lookup.
