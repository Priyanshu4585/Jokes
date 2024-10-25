Jokes Web App 🤣
A fun and easy-to-use web app to get jokes on demand! Pick a category, customize your preferences, and get a joke that’s sure to make you and your friends laugh.

Table of Contents
Features
Tech Stack
Setup
Usage
Screenshots
API Reference
Future Improvements
License
Features
Random Joke Selection: Choose a joke from any category or customize your own!
Custom Categories: Includes categories like Programming, Dark, Puns, and more.
Dynamic Joke Fetching: Fetches jokes in real time using JokeAPI.
Error Handling: Provides feedback in case of issues with the joke API.
Tech Stack
Frontend: HTML, CSS, EJS (Embedded JavaScript templates)
Backend: Node.js, Express.js
HTTP Client: Axios for API requests
API: JokeAPI
Setup
Clone the Repository:
bash
Copy code
git clone https://github.com/your-username/jokes-web-app.git
Navigate to the Project Directory:
bash
Copy code
cd jokes-web-app
Install Dependencies:
bash
Copy code
npm install
Run the App:
bash
Copy code
npm start
The app will start at http://localhost:3000.
Usage
Visit the homepage.
Select a joke category:
Choose "Any" for a random joke.
Choose "Customize" to enable multiple joke categories (Programming, Dark, etc.).
Click "Submit" to fetch a joke and enjoy the laughter! 🎉

API Reference
This app uses the JokeAPI, which allows for customizable categories and formats. Here’s how we’re using it:

Base URL: https://v2.jokeapi.dev/joke/
Parameters:
categories: Customize joke types (e.g., "Programming, Dark").
format: Set to txt for plain text jokes.
Future Improvements
More Categories: Add additional joke categories as they become available.
Improved UI: Design enhancements to make the app more engaging.
Add Joke Rating: Allow users to rate jokes or mark their favorites.
License
This project is licensed under the MIT License.
