React Programming Joke App

A simple React application that demonstrates handling side effects using the useEffect hook. The app fetches a random programming joke from an API on load and allows the user to fetch a new joke by clicking a button.

## Features
Fetch and display a programming joke on page load
Fetch a new joke on button click
Shows a loading message while fetching
Demonstrates proper use of React useEffect and component props

## Setup Instructions
1. Clone the repository
git clone <your-repo-url>
cd react-side-effects-vite
2. Install dependencies
npm install
3. Run the development server
npm run dev
4. Open your browser at the URL shown in the terminal (usually http://localhost:5173/)
5. Run tests
npm test
Verifies that the app fetches jokes and updates correctly

## Project Structure
src/
├─ App.jsx          # Main component managing state & fetch logic
├─ FetchButton.jsx   # Button component that triggers a new joke fetch
├─ JokeDisplay.jsx  # Displays joke or loading state
├─ App.jsx        # Entry point
├─ index.css       # Optional styling
└─ __tests__/       # Unit tests for components

## Usage
Open the app in your browser
See a programming joke displayed on page load
Click “Get a New Joke” to fetch another joke
Observe the loading message while the new joke is fetched

## API Used
JokeAPI - Programming Jokes
Returns a single programming joke in JSON format

Notes

## AUTHOR
Ouko Sharon @2026