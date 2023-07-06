Slot Machine
This is a Python program that simulates a slot machine game. The user can deposit money, choose the number of lines to bet on, and place bets on each line. The program generates random symbols in a grid-like structure and determines the winnings based on the matching symbols and bet amounts.

How to Run the Program
Ensure you have Python installed on your system.
Copy the code into a Python file (e.g., slot_machine.py).
Open a terminal or command prompt and navigate to the directory where the file is located.
Run the program by executing the command python slot_machine.py.
Follow the instructions provided in the terminal to interact with the slot machine.
Program Features
Deposit: The user can deposit a specified amount of money to start the game.
Number of Lines: The user can choose the number of lines to bet on (between 1 and 3).
Bet Amount: The user can enter the bet amount for each line (between 1 and 100).
Spin: The program generates a random grid of symbols based on the chosen number of lines and bet amounts.
Winnings: The program checks for matching symbols in each line and calculates the total winnings.
Display: The program displays the generated symbols, the amount won, and the winning lines.
Balance: The program keeps track of the user's balance throughout the game.
Quit: The user can choose to quit the game at any time.
Program Structure
The program consists of the following main components:

deposit(): Prompts the user to enter the amount of money they want to deposit. Validates the input and returns the deposited amount.
get_number_of_lines(): Prompts the user to enter the number of lines they want to bet on. Validates the input and returns the chosen number of lines.
get_bet(): Prompts the user to enter the bet amount for each line. Validates the input and returns the chosen bet amount.
spin(balance): Simulates a spin of the slot machine. Generates random symbols, calculates the winnings, and updates the balance accordingly. Returns the net change in balance (winnings - total bet).
check_winnings(columns, lines, bet, values): Checks for matching symbols in each line and calculates the total winnings based on the bet amount and symbol values.
get_slot_machine_spin(rows, cols, symbols): Generates a random grid of symbols based on the specified number of rows, columns, and available symbols.
print_slot_machine(columns): Displays the generated symbols in a grid-like format.
main(): The main entry point of the program. Manages the flow of the game, handles user input, and tracks the balance.
Game Rules
The user starts the game by depositing a specified amount of money.
The user can choose to spin the slot machine or quit the game.
For each spin, the user selects the number of lines to bet on (between 1 and 3) and the bet amount for each line (between 1 and 100).
The program generates a random grid of symbols based on the chosen parameters.
The program checks for matching symbols in each line and calculates the total winnings based on the bet amount and symbol values.
The program displays the generated symbols, the amount won, and the winning lines.
The user's balance is updated with the net change (winnings - total bet) after each spin.
The game continues until the user chooses to quit or runs out of balance.
Feel free to modify and enhance the code as per your requirements
