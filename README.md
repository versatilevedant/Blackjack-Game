# **Blackjack Game (Python)**

*A console-based **Blackjack** game developed in **Python**, where the player competes against the dealer to get a hand value closest to **21** without going over. This classic card game includes card dealing, bet management, and logic to handle outcomes such as busts, wins, ties, and more*.

---

### **Features:**
- **Card Dealing**: Randomly deals cards to the player and dealer from a shuffled deck.
- **Bet Management**: Players can place bets before each round, and the game will manage their balance based on wins or losses.
- **Player Actions**: Players can choose to "Hit" (get a card) or "Stand" (keep their current hand).
- **Dealer Logic**: The dealer plays automatically according to standard Blackjack rules (e.g., the dealer must "hit" if the hand is below 17).
- **Game Outcomes**: The game checks for various outcomes:
  - **Bust**: Player or dealer goes over 21.
  - **Win**: The player gets closer to 21 than the dealer without going over.
  - **Tie**: Both the player and dealer have the same hand value.
- **Replay Option**: After each round, players can choose to **replay** or quit.

---

### **How to Play:**
1. Clone or download this repository.
2. Run the `blackjack.py` file in your terminal.
3. Players will start by placing their bets.
4. Players will be dealt two cards, and the dealer will have one card face up.
5. Players can choose to "Hit" to draw more cards or "Stand" to keep their current hand.
6. The dealer will play automatically based on predefined rules.
7. After each round, the outcome (win, loss, or tie) will be displayed, and players can choose to replay or quit.

---

### **Game Flow:**
1. **Place Bet**: The player places a bet before each round.
2. **Card Dealing**: Both the player and dealer receive two cards.
3. **Player's Turn**: The player can either "Hit" to receive another card or "Stand" to keep their current hand.
4. **Dealer's Turn**: The dealer automatically draws cards according to standard Blackjack rules.
5. **Outcome Check**: After the dealer's turn, the game checks whether the player or dealer has won, busted, or if it's a tie.
6. **Replay**: Players are prompted to replay or quit after each round.

---

### **Demonstration:**

Here is a Demonstartion showing the game in action:

![Screenshot](https://github.com/user-attachments/assets/bb5abda8-cdbc-4c3f-86b9-fe29e21b1ac1)

---


### **Technologies Used:**
- **Python 3**: The programming language used for the game logic and interactions.
- **Command-line Interface (CLI)**: The game is played via a terminal/command-line interface with user prompts for input.

---

### **Installation:**
To get started, simply clone this repository to your local machine:

```bash
git clone https://github.com/your-username/blackjack.git
