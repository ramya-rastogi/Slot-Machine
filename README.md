# 🎰 Python Slot Machine Game

A fun and interactive **command-line slot machine** built in Python!  
This project allows players to deposit money, place bets on multiple lines, spin the slot machine, and win based on matching symbols.

---

## 🧩 Features

- 💰 **Deposit System** – Add funds before starting the game.  
- 🎯 **Multiple Line Betting** – Bet on 1 to 3 lines per spin.  
- 🎲 **Randomized Spins** – Each spin randomly selects symbols for every slot column.  
- 🏆 **Winnings Calculation** – Earn based on symbol values and number of winning lines.  
- 🔁 **Replay Option** – Continue spinning until you quit or run out of balance.  

---

## 🧠 Game Rules

- You can bet on up to **3 lines** at a time.  
- Each line can have a bet between **₹1000 and ₹50000**.  
- Symbols appear with the following frequency and payout values:

| Symbol | Frequency | Value |
|:-------:|:----------:|:------:|
| A | 2 | 5 |
| B | 4 | 4 |
| C | 6 | 3 |
| D | 8 | 2 |

- You **win** if all symbols in a line match across the columns.

---

## 🖥️ How to Play

-  **Run the program**
   ```bash
   python slot_machine.py
- Deposit some money to start.
- Choose the number of lines you want to bet on (1–3).
- Enter your bet amount per line.
- Spin!
- The machine will display the slot results and your winnings.
- You can play again or quit anytime by typing q.

---

## 🧮 Example Gameplay

````text
What would you like to deposit? 5000  
Enter number of lines you want to bet on (1-3)? 3  
What would you like to bet on each line? 1000  
You are betting 1000 on 3 lines. Total bet is equal to 3000  

A | D | A  
B | A | A  
A | A | A  

YOU WON 5000.  
You won on lines: 3  
Current Balance is 7000  
Press Enter to play (q to quit)  
````
---

## ⚙️ Project Structure
```bash
slot_machine.py    # Main Python file containing the entire game logic  
README.md          # Project documentation  

```
---

## 🧰 Concepts Used

- Random module (random.choice)
- Functions and loops
- Conditional statements
- User input handling
- Data structures (lists, dictionaries


