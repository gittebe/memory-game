# 🎮 Memory Game (React + useReducer)

## 📌 Project Description
This is a classic Memory Game built with React using useReducer for state management. The project is divided into multiple branches so we can work in parallel without interfering with each other’s code.

## 🚀 Installation & Setup
### 🔹 1. Clone the repository   
```bash
git clone https://github.com/joheri1/memory-game
cd memory-game
```   

### 🔹 2. Install dependencies   
```bash
npm install
```   

### 🔹 3. Start the development server   
```bash
npm run dev
```   
This will run the project on `http://localhost:5173/` (or another available port).   

## 🛠 Branches & Tasks
Each branch contains a specific feature, allowing us to work independently.

### 🔹 1. Project Setup & Initial UI   
Branch: `setup-ui`   
Description: Set up the React project and add basic UI components.   
Tasks:   
✅ Initialize the project with Vite (npm create vite@latest memory-game --template react)   
✅ Create GameBoard and Card components   
✅ Add a basic grid layout with CSS   
   
### 🔹 2. useReducer – Manage Card States   
Branch: `useReducer-cards`   
Description: Implement useReducer to manage the state of the cards (flipped, matched, hidden).   
Tasks:   
✅ Create a reducer function to manage the game state   
✅ Add actions to flip cards and check for matches   
✅ Ensure non-matching cards flip back after a short delay   
    
### 🔹 3. useReducer – Manage Game Statistics   
Branch: useReducer-score   
Description: Use useReducer to track game statistics (attempts, score, and time).   
Tasks:   
✅ Implement a counter for attempts   
✅ Add a scoring system (e.g., +10 points per match)   
✅ Optionally, include a timer   

### 🔹 4. UI – Card Styling & Animations   
Branch: `ui-card-styling`   
Description: Add CSS for the cards, including flip animations.   
Tasks:   
✅ Style the cards (size, colors, etc.)   
✅ Add a flip animation when a card is clicked   
✅ Ensure the animation is smooth and visually appealing   
   
### 🔹 5. UI – Responsive Layout & Game Screen   
Branch: `ui-responsive`   
Description: Improve the overall UI for different screen sizes.   
Tasks:   
✅ Make the game responsive for mobile, tablet, and desktop   
✅ Improve grid layout for different screen sizes    
✅ Style the game-over screen   
   
### 🔹 6. UI – Accessibility   
Branch: `ui-a11y`   
Description: Enhance the game's accessibility to ensure it is user-friendly for all players, including those using screen readers or keyboard navigation.   
Tasks:   
✅ Improve keyboard navigation – Ensure users can play the game using only the keyboard (e.g., using Tab and Enter to navigate and flip cards).   
✅ Add ARIA attributes – Implement aria-labels, role="button", and other accessibility tags for screen readers.   
✅ Increase color contrast – Adjust colors to meet WCAG (Web Content Accessibility Guidelines) for better readability.   
✅ Make the game responsive – Ensure a smooth experience on mobile, tablet, and desktop.   
✅ Improve grid layout – Optimize spacing and scaling across different screen sizes.   
✅ Enhance the game-over screen – Make sure it is clearly visible and easy to navigate.   
   
### 🔹 7. Add a "Game Over" Screen   
Branch: `game-over-screen`   
Description: Display a message when all pairs have been found.   
Tasks:   
Detect when all cards are matched   
✅ Show a “You Win!” message   
✅ Add a “Play Again” button to restart the game   

## 🪜 Strech goals   
### 1. Use `useReducer` to:   
✅ Streak Rewards – Players earn a reward if they play for x consecutive days.   
✅ Leaderboard & High Scores – Track the best times and scores in localStorage(?).   
✅ Unlockable Themes – Players can unlock new card designs after completing certain challenges.   
✅ Sound Effects & Music – Add fun sound effects when flipping/matching cards.   
✅ Multiplayer Mode – Compete with a friend to see who finds the most pairs!   
✅ Custom Difficulty Levels – Let players choose between Easy (4x4), Medium (6x6), or Hard (8x8) grid sizes.

### 2. Make it a real mobile app by trying out `React Native`   
   
## 🌲 How We Work with Branches   
Check the README and choose a branch to work on   
   
Create a new local branch from main:   
```bash
git checkout -b useReducer-cards
```   
When a branch is completed, create a pull request and request a review   

Once approved, merge it into main before starting the next branch   
   
### Happy coding! 🚀   
