# My Todos List

A clean and lightweight Todo web app built with React. It helps users add and delete daily tasks, with automatic persistence in browser local storage.

## Features

- Add todos with a title and description
- Delete existing todos
- Persist todos in `localStorage`
- Simple client-side routing with Home and About pages
- Responsive Bootstrap-based UI

## Tech Stack

- React 17
- React Router DOM 5
- Create React App
- Bootstrap (via classes in components)

## Getting Started

### Prerequisites

- Node.js (LTS recommended)
- npm

### Installation

```bash
git clone https://github.com/MahirAzmain/My-Todos-List.git
cd My-Todos-List
npm install
```

### Run in Development

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

- `npm start` — starts the development server
- `npm test` — runs tests in watch mode
- `npm run build` — builds the app for production
- `npm run eject` — ejects CRA config (irreversible)

## Project Structure

```text
src/
  MyComponents/
    AddTodo.js
    TodoItem.js
    Todos.js
    Header.js
    Footer.js
    About.js
  App.js
  index.js
```

## How It Works

- The app initializes todos from `localStorage`.
- New todos are appended with an incremental serial number.
- Deleting a todo updates the state and storage.
- A `useEffect` syncs todos to `localStorage` whenever the list changes.

## Notes

- This project currently has no explicit license file.

## Contributing

Contributions are welcome. Fork the repo, create a feature branch, and open a pull request.
