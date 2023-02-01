<!--hide-->
# Create a TicTacToe CLI using Python
<!--endhide-->

You will practice:
1. Python lists/arrays.
2. Creating a two dimensional matrix with Python
3. Using the while loop to avoid your application from ending.
4. Using conditionals.
5. Implementing a CLI (command line interface).

## 📝 Instructions

Fill the content of the methods `play`, `check_for_winner`, `new_game` and the commands inside the while needed to make the TicTacToe behave like this picture.

```python
def play(position):
def check_for_winner():
def new_game():
```

1. There are two players `X` and `O`.
2. `X` always starts playing.
3. To make a play, the command its `play <position>` for example: `play 1` will play for the current player on the position 1 in the list (the second one)
4. If `X` makes a play, it's `O`'s turn (automatically) and vice-versa.
4. Every time aony player makes a play you have to check for winners.
5. The game ends when any of the players finally makes a winning combination.
6. The game can be reset (start again) any time.
7. The user must stop the game and exit anytime (releasing the terminal).

## 🌱 How to start this project

Do not clone this repository.

1. The first step to start coding is cloning the [python boilerplate](https://github.com/4GeeksAcademy/flask-rest-hello) on your local computer or gitpod.

a) If using Gitpod you can clone the boilerplate by [clicking here](https://github.com/4GeeksAcademy/flask-rest-hello).
b) If working locally type the following command from your command line: `git clone https://github.com/4GeeksAcademy/flask-rest-hello`.

💡 Important: Remember to create a new repository, update the remote (`git remote set-url origin <your new url>`), and upload the code to your new repository using `add`, `commit` and `push`.

2. Run the app by typing on the terminal:

```bash
$ python3 app.py
```
