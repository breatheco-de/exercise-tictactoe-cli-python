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

Hay dos formas de hacerlo:

a) Abrir este enlace con [Codespaces](https://4geeks.com/es/lesson/tutorial-de-github-codespaces) (recomendado) o [Gitpod](https://4geeks.com/es/lesson/como-utilizar-gitpod) en tu navegador: https://github.com/codespaces/new/?repo=4GeeksAcademy/python-hello

b) Clonar el siguiente repositorio localmente en tu computador:

```sh
$ git clone https://github.com/4GeeksAcademy/python-hello
```

### Pasos

- Si trabajas localmente, debe tener python [instalado](https://4geeks.com/es/how-to/como-instalar-python).

- Deberías abrir el terminal en la ruta de esta plantilla y ejecutar `$ python3 app.py`, si todo funciona correctamente, debería mostrar `Hello World` en el terminal.

- Puedes probar tu código escribiendo `$ python3 test.py`.

💡 Importante: Recuerda actualizar el `remote` del proyecto con el de tu repositorio usando `git remote set-url origin <your new url>`, y luego guardar tu código en tu nuevo repositorio usando `add`, `commit` y `push`.

</onlyfor>









