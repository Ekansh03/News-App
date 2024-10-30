Project Overview
The News App is a web application designed to fetch and display the latest news articles on various topics using the News API. Users can navigate through predefined categories like IPL, Sports, and Finance or use the search bar to find news on specific topics. The application is built with HTML, CSS, and JavaScript to provide a responsive and dynamic user experience.

Features
Navigation Bar: Allows users to choose from predefined categories like IPL, Sports, and Finance.
Search Bar: Enables users to search for news articles using a keyword.
Responsive Layout: Uses Flexbox to ensure the layout adjusts across different screen sizes.
Dynamic News Cards: Displays news articles with images, titles, source information, and descriptions.
Interactive Cards: Clicking on a news card opens the full article in a new tab.

Project Structure
graphql
Copy code
📁 News App
│
├── 📁 assets
│   └── logo.png             # Logo image used in the navigation bar
│
├── 📄 index.html            # Main HTML file containing the structure of the application
├── 📄 style.css             # CSS file for styling the application
├── 📄 script.js             # JavaScript file for fetching and displaying news articles
└── 📄 README.md             # Project documentation

Technologies Used
HTML5: For the overall structure of the webpage.
CSS3: For styling the layout and components, and providing a responsive user experience.
JavaScript (ES6): For fetching data from the News API and dynamically populating the news cards.
How to Use
Download or Clone the Repository:
You can clone this project by using the following command:

bash
Copy code
git clone <repository_url>
Add API Key:
You will need an API key from News API. Sign up and get an API key. Then, replace the placeholder API_KEY in the script.js file with your own key:

javascript
Copy code
const API_KEY = "YOUR_API_KEY";
Open index.html in your browser:
Double-click on the index.html file to open it in your default browser.

Using the Application:

Navigation: Click on the navigation items like 'IPL', 'Sports', or 'Finance' to view related news.
Search: Enter a keyword in the search bar and click the search button to fetch relevant news articles.
Code Explanation
HTML
The HTML file defines the structure of the application. It includes:

A navigation bar with a logo and predefined category links.
A search bar for entering queries.
A section to display news cards using a reusable template.
CSS
The CSS file is used to style the entire application:

Flexbox is used to align and distribute elements evenly.
Root Variables (--primary-text-color, --accent-color, etc.) provide a consistent color scheme.
Responsive Design: The CSS ensures the app works well on various devices.
Card Hover Effects provide interactive feedback when hovering over news cards.
JavaScript
The JavaScript file handles fetching data from the News API and dynamically populating the news cards:

Fetching News: Uses the fetchNews function to call the News API based on the selected category or user input.
Binding Data: Populates the HTML template with the fetched articles.
Interactivity: Provides functionality to navigate between categories and perform keyword searches.
Future Enhancements
Add Pagination: To allow users to view more news articles beyond the initial set of results.
User Authentication: To allow users to save their favorite articles.
Improved Styling: Additional CSS transitions and animations for a more engaging user experience.
License
This project is open-source and available under the MIT License. Feel free to contribute, modify, and use it as per your requirements.
