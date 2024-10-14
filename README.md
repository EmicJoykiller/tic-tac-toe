This project is a full implementation of a Tic-Tac-Toe game built using React. It showcases key features like state management, event handling, and conditional rendering in React. The game consists of three main components: Square, Board, and Game.

Square Component: Responsible for rendering individual squares on the game board. Each square takes a value (X or O) and a click event handler to update the game state when clicked.

Board Component: Manages the state of the entire game board. It tracks which player’s turn it is, updates the board when a square is clicked, and checks for a winner after each move. The calculateWinner function uses predefined winning combinations to determine if a player has won. If no winner is detected, the next player's turn is displayed.

Game Component: The main component that manages the game history, allowing users to view and return to previous game states through a move history interface. The use of useState hooks enables dynamic game state management, and the game history is rendered as an ordered list of buttons, each representing a move. Players can navigate to any previous move, which enhances the interactivity.

The project follows a component-based architecture and highlights React’s efficient rendering model through the re-rendering of only the affected parts of the interface. Additionally, the game is styled with a simple CSS layout, and the application is rendered in the browser using the createRoot method from ReactDOM.
