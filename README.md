# Snake 🐍 Water 💧 Gun 🔫 Game (Python)

This is a simple **Snake–Water–Gun** game implemented in Python. It is similar to the classic **Rock–Paper–Scissors** game, where the user plays against the computer.

---

## 📌 Game Rules

Each option has a numeric value:

* **Snake** → `1`
* **Water** → `-1`
* **Gun** → `0`

### Winning Conditions

* Snake drinks Water → **Snake wins**
* Water damages Gun → **Water wins**
* Gun kills Snake → **Gun wins**
* Same choices → **Draw**

---

## 🧠 How the Program Works

1. The computer randomly selects one option from `snake`, `water`, or `gun`.
2. The user inputs their choice using:

   * `s` for Snake
   * `w` for Water
   * `g` for Gun
3. The program compares both choices using conditional statements.
4. The result (Win / Lose / Draw) is displayed.

---

## ▶️ How to Run the Game

1. Make sure Python is installed on your system.
2. Save the code in a file, for example:

   ```
   snake_water_gun.py
   ```
3. Open a terminal or command prompt.
4. Run the program using:

   ```
   python snake_water_gun.py
   ```
5. Enter your choice when prompted.

---

## 🧪 Example Output

```
Enter your choice: s
you chose snake
computer chose water
you win!
```

---

## 🛠️ Technologies Used

* Python 3
* `random` module

---
👤 Author

Bikram Pal
CSE (AI & ML) Student


---

## 📄 License

This project is for learning and practice purposes. Feel free to modify and improve it.

Happy Coding! 🚀
