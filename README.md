📝 CLI Todo App

A simple and functional command-line Todo app built with Node.js using `commander` for CLI interface and `chalk` for colorful outputs. All todos are saved to a `todo.txt` file.

📦 Features

- Add new todos
- Show all todos (color-coded by completion)
- Delete last todo
- Edit a specific todo
- Mark a todo as complete
🚀 How to Use

1. Clone the repository and install dependencies:

```bash
npm install
```

2. Run the CLI using:

```bash
node index.js <command>
```

Commands

```bash
node index.js add "Buy groceries"
node index.js show
node index.js delete
node index.js edit "Buy groceries" "Buy vegetables"
node index.js complete "Buy vegetables"
```

🛠 Built With

- Node.js
- Commander.js
- Chalk
- FS module

📁 File

- `todo.txt` – stores your todos line by line
