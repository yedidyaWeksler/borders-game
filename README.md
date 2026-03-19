# Neighbors Game: Border Quiz

An interactive, educational web application designed to challenge and improve your geographical knowledge. The game tasks players with identifying all countries or US states that share a land border with a selected target.

## Key Features

- Dual Game Modes: Switch between practicing world countries or the 50 states of the USA.
- Advanced Autocomplete: Real-time search suggestions with full keyboard navigation support (Arrow keys to navigate, Enter to select).
- Progressive Hint System: A dynamic hint button that reveals letters of a random missing neighbor using an underscore placeholder format (e.g., I _ _ _ _ _).
- Game Statistics: A post-game summary modal displaying your accuracy percentage (based on wrong guesses) and the number of hints used.
- Multilingual Support: Full interface and database support for Hebrew, English, and Arabic.
- Responsive Interactive Map: Automatic zooming and focusing on the selected target, with color-coded feedback for found neighbors.

## Geopolitical and Data Accuracy

To provide a consistent and professional user experience, the application includes custom logic to handle geographical data complexities:

- Territorial Merging: Disputed or non-sovereign territories are merged into their widely recognized sovereign states for mapping purposes (e.g., Kosovo with Serbia, Western Sahara with Morocco, Somaliland with Somalia).
- Border Symmetry: The engine ensures that all borders are symmetrical; if Country A borders Country B, the game logic verifies that Country B also borders Country A.
- Island Filtering: Territories without land borders (islands) are automatically filtered out from the practice list to ensure playable game sessions.

## Technologies Used

- Leaflet.js: For interactive map rendering and geographic polygon handling.
- REST Countries API: To fetch real-time country data and international border information.
- Vanilla JavaScript: Core game logic, state management, and custom sound engine.
- HTML5 & CSS3: Responsive design with native RTL (Right-to-Left) support for Hebrew and Arabic.
- Canvas Confetti: Visual celebration effects upon game completion.

## How to Play

- Select the game type (World or US States) and your preferred language.
- Pick a target to practice from the dropdown menu or click "Random".
- Start typing the names of neighboring territories.
- Use the hint button if you get stuck to reveal letters.
- Identify all neighbors to win and view your performance statistics.

---
**Developed by Yedidya Weksler**
