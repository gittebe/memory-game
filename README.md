# 🎮 Memory Game (React + useReducer)

📌 Project Description
This is a classic Memory Game built with React using useReducer for state management. The project is divided into multiple branches so we can work in parallel without interfering with each other’s code.

🚀 Installation & Setup
🔹 1. Clone the repository
bash
Kopiera
Redigera
git clone <your-repo-url>
cd memory-game

🔹 2. Install dependencies
bash
Kopiera
Redigera
npm install

🔹 3. Start the development server
bash
Kopiera
Redigera
npm run dev
This will run the project on http://localhost:5173/ (or another available port).

🛠 Branches & Tasks
Each branch contains a specific feature or part of the UI, allowing us to work independently.

🔹 1. Project Setup & Initial UI
Branch: setup-ui
Description: Set up the React project and add basic UI components.
Tasks:
Initialize the project with Vite (npm create vite@latest memory-game --template react)
Create GameBoard and Card components
Add a basic grid layout with CSS

🔹 2. useReducer – Manage Card States
Branch: useReducer-cards
Description: Implement useReducer to manage the state of the cards (flipped, matched, hidden).
Tasks:
Create a reducer function to manage the game state
Add actions to flip cards and check for matches
Ensure non-matching cards flip back after a short delay

🔹 3. useReducer – Manage Game Statistics
Branch: useReducer-score
Description: Use useReducer to track game statistics (attempts, score, and time).
Tasks:
Implement a counter for attempts
Add a scoring system (e.g., +10 points per match)
Optionally, include a timer

🔹 4. UI – Card Styling & Animations
Branch: ui-card-styling
Description: Add CSS for the cards, including flip animations.
Tasks:
Style the cards (size, colors, etc.)
Add a flip animation when a card is clicked
Ensure the animation is smooth and visually appealing

🔹 5. UI – Responsive Layout & Game Screen
Branch: ui-responsive
Description: Improve the overall UI for different screen sizes.
Tasks:
Make the game responsive for mobile, tablet, and desktop
Improve grid layout for different screen sizes
Style the game-over screen

🔹 6. Add a "Game Over" Screen
Branch: game-over-screen
Description: Display a message when all pairs have been found.
Tasks:
Detect when all cards are matched
Show a “You Win!” message
Add a “Play Again” button to restart the game

✅ How We Work with Branches
Check the README and choose a branch to work on
Create a new local branch from main:
bash
git checkout -b useReducer-cards

When a branch is completed, create a pull request and request a review
Once approved, merge it into main before starting the next branch

Happy coding! 🚀
