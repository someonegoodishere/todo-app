# To-Do App

A simple, single-file to-do list web app. No build step, no dependencies, no framework.

## Features

- Add tasks via the input field (Enter key or the Add button)
- Mark tasks complete with a checkbox (strikethrough styling)
- Delete individual tasks with the x button
- Clear all completed tasks at once
- Live remaining-task counter
- Tasks persist across reloads via localStorage (key: todo-tasks)

## Usage

Open todo-app.html in any modern browser. That is the whole setup.

## Notes

- Task text is inserted with textContent, so HTML in a task is rendered as literal text.
- If localStorage is unavailable (e.g. private browsing), the app falls back to in-memory storage instead of failing.

## Status

Ready.
