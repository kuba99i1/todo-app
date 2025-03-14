# Simple To-Do App

## Description
To-Do App is a simple task manager that allows users to add, edit, view, and delete tasks. The application works both as a command-line interface (CLI) and a graphical user interface (GUI).

---

## Requirements
- Python 3.x
- FreeSimpleGUI (for the GUI version)

To install FreeSimpleGUI, run:
```sh
pip install FreeSimpleGUI


---

## Usage (CLI)
Run the command-line version:
```sh
python cli.py
```
Available commands:
- `add [task_name]` – adds a task
- `show` – displays the list of tasks
- `edit [task_number]` – edits a task
- `complete [task_number]` – removes a task
- `exit` – exits the application

---

## Usage (GUI)
Run the graphical version (if you have `gui.exe` in the `dist` folder):
```sh
dist/gui.exe
```
To run it from Python:
```sh
python gui.py
```

---

## Project Structure
- `cli.py` – command-line version of the app
- `gui.py` – graphical user interface version
- `functions.py` – handles the `todos.txt` file
- `todos.txt` – stores tasks (required for `gui.exe` to work)
- `dist/` – folder containing the compiled GUI version:
  - `dist/gui.exe` – compiled application
  - `dist/todos.txt` – task file (must be in the same folder as `gui.exe`)

---
