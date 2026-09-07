# To-Do List

A simple and responsive task-management app built with React and Vite. Add tasks with due dates, view them in a clean list, and remove them when they are complete.

## Features

- Add a task with a due date
- View all added tasks in one place
- Delete tasks from the list
- Empty-state message when no tasks are available
- Responsive layout using Bootstrap

## Built With

- React 19
- Vite
- Bootstrap 5
- JavaScript (ES modules)
- CSS Modules

## Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) and npm installed.

### Installation

1. Clone the repository:

	```bash
	git clone https://github.com/Arunkasana001/TO-DO-LIST.git
	```

2. Move into the application directory:

	```bash
	cd TO-DO-LIST/TO-DO-LIST
	```

3. Install the dependencies:

	```bash
	npm install
	```

4. Start the development server:

	```bash
	npm run dev
	```

5. Open the local URL shown in the terminal, usually `http://localhost:5173`.

## Available Scripts

Run these commands from the `TO-DO-LIST/TO-DO-LIST` directory:

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Create a production build |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Check the code with ESLint |

## Project Structure

```text
TO-DO-LIST/
└── TO-DO-LIST/
	 ├── public/
	 ├── src/
	 │   ├── components/
	 │   │   ├── AddTodo.jsx
	 │   │   ├── AppName.jsx
	 │   │   ├── TodoItem.jsx
	 │   │   ├── TodoItems.jsx
	 │   │   └── WelcomeMessage.jsx
	 │   ├── App.jsx
	 │   ├── App.css
	 │   └── main.jsx
	 ├── index.html
	 ├── package.json
	 └── vite.config.js
```

## Data Storage

Tasks are stored in React component state and are not persisted to a database or browser storage. Refreshing the page clears the current task list.

## License

This project is available for personal and educational use.