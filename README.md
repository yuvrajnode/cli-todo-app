# CLI Todo App

A command-line todo list for Node.js, built with [Commander](https://github.com/tj/commander.js) for argument parsing and [Chalk](https://github.com/chalk/chalk) for coloured output. Todos are stored as lines in `todo.txt`.

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

## Install

```bash
git clone https://github.com/yuvrajnode/cli-todo-app.git
cd cli-todo-app
npm install
```

## Usage

```bash
node index.js <command> [arguments]
```

| Command | Description | Example |
|---|---|---|
| `add <todo>` | Add a todo | `node index.js add "Buy groceries"` |
| `show` | List all todos, colour-coded by status | `node index.js show` |
| `edit <old> <new>` | Rename a todo | `node index.js edit "Buy groceries" "Buy vegetables"` |
| `complete <todo>` | Mark a todo as done | `node index.js complete "Buy vegetables"` |
| `delete` | Remove the most recent todo | `node index.js delete` |
| `--help` | Show all commands | `node index.js --help` |

## License

MIT © Yuvraj Singh
