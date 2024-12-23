<!--hide-->
# Crea una CLI de TicTacToe usando Python
<!--endhide-->

Vas a practicar:
1. Listas/matrices de Python.
2. Crear una matriz bidimensional con Python.
3. Usar el bucle while para evitar que su aplicación finalice.
4. Usar condicionales.
5. Implementar una interfaz de línea de comandos (CLI).

## 📝 Instrucciones

Rellena el contenido de los métodos `play`, `check_for_winner`, `new_game` y los comandos dentro del while necesarios para que el TicTacToe se comporte como la imagen.

```python
def play(position):
def check_for_winner():
def new_game():
```

1. Hay dos jugadores `X` y `O`.
2. `X` siempre empieza a jugar.
3. Para hacer una jugada, el comando es `play <position>` por ejemplo: `play 1` jugará para el jugador actual en la posición 1 de la lista (la segunda).
4. Si `X` hace una jugada, es el turno de `O` (automáticamente) y viceversa.
4. Cada vez que algún jugador haga una jugada, hay que comprobar si hay ganador.
5. El juego termina cuando alguno de los jugadores haga una combinación ganadora.
6. El juego se puede reiniciar (empezar de nuevo) en cualquier momento.
7. El usuario debe detener el juego y salir en cualquier momento (liberando el terminal).

<onlyfor saas="false" withBanner="false">
  
## 🌱 Cómo empezar este proyecto

No clones este repositorio porque usaremos una plantilla diferente.  

Recomendamos abrir el `boilerplate de python`,  utilizando una herramienta de aprovisionamiento como [Codespaces](https://4geeks.com/es/lesson/tutorial-de-github-codespaces) (recomendado) o [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternativamente, puedes clonar el repositorio de [GitHub](https://4geeks.com/es/how-to/como-clonar-un-repositorio-de-github) en tu computadora local utilizando el comando `git clone`.  

Este es el repositorio que necesitas abrir o clonar:  

```sh
$ git clone https://github.com/4GeeksAcademy/flask-rest-hello
```

💡 Importante: Recuerda crear un nuevo repositorio, actualizar el remoto (`git remote set-url origin <your new url>`), y subir el código a tu nuevo repositorio usando `add`, `commit` y `push`.

Luego, ejecuta la aplicación escribiendo en el terminal:
bash

```bash
$ python3 app.py
```
</onlyfor>









