# DiceGame_Project1

Overview:
The Dice Game is a simple web-based game where two players roll virtual dice by refreshing the page, and the player with the higher roll wins. If both players roll the same number, the game ends in a draw.

Structure:

	1.	HTML (dicee.html):
	•	The game is hosted in a single HTML page. It includes a container that holds two dice images and a header that displays the result of the game.
	•	There are two dice, each associated with a player (Player 1 and Player 2).
	•	The images of the dice are initially set to show six dots (dice6.png).
	•	The page includes external links to the Google Fonts API for custom fonts and a CSS stylesheet for styling.
	2.	CSS (styles.css):
	•	The game is visually styled using CSS. The container is centered, and text is aligned to the center as well.
	•	The body of the page has a dark background color (#393E46), with fonts and other elements styled using cursive fonts (‘Lobster’ for headings and ‘Indie Flower’ for other text).
	•	The colors are chosen to provide a vibrant and playful look, with mint green (#4ECCA3) for text and white for footer text ￼.
	3.	JavaScript (index.js):
	•	The game logic is implemented using JavaScript. When the page is refreshed, two random numbers between 1 and 6 are generated, representing the roll of each player’s die.
	•	Based on the generated numbers, the corresponding dice images are selected and displayed by changing the src attribute of the image elements.
	•	The script then compares the two numbers to determine the winner. If Player 1’s number is higher, a message declaring “🚩 Player 1 Wins” is displayed at the top of the page. If Player 2’s number is higher, it displays “🚩 Player 2 Wins”. In case of a tie, it displays “🚩 It’s a DRAW” ￼ ￼.

Gameplay:

	•	To play the game, users simply refresh the webpage. Each refresh represents a new game round, with the dice rolling and the winner being declared instantly based on the outcome of the dice.

This Dice Game is a simple yet engaging way to simulate the fun of rolling dice and adds a bit of competitive excitement with its winner declaration.
it a simple BUT fun Dice Game!!
Its my first PROJECT created using the implementations of HTML , CSS and Java Script.
Hope you LIKE IT.
