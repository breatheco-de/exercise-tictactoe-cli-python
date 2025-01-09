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

<onlyfor saas="false" withBanner="false">
  
## 🌱 How to start this project

There are 2 ways to start: 

a) Open this link in your browser with [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recommended) or [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod): https://github.com/codespaces/new/?repo=4GeeksAcademy/python-hello

b) You can clone the following repository on your local computer:

```bash
$ git clone https://github.com/4GeeksAcademy/python-hello
```

### Steps

- If working locally, you should have python [installed](https://4geeks.com/how-to/how-to-install-python).

- You should open the terminal on the path of this template and run `$ python3 app.py`, if everything works correctly, it should show `Hello World` on the terminal.

- You can test your code by typing: `$ python3 test.py`.

💡 Important: Remember to create a new repository, update the remote (`git remote set-url origin <your new url>`), and upload the code to your new repository using `add`, `commit` and `push`.

</onlyfor>
