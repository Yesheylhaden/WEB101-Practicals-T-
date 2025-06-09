# Practical_6: Todo List Application with Zustand

A minimal yet powerful Todo List application developed with React and Zustand for efficient state handling. This project showcases how to manage shared state and persist data in a simple React environment without the need for prop drilling or verbose setups.

---

## Table of Contents:

- [Installation](#installation)
- [Usages](#usages)
- [Features](#features)
- [Technologies](#technologies)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)

---

## Installation:

1. **Create Project with Vite**
npx create-vite@latest todo-zustand
cd todo-zustand

2. **Install Dependencies**
npm install zustand

## Usages:

- Enter a new task into the input field and press enter to add it to the list.
- Click on a task to mark it as done or undone.
- Use the trash icon to delete a task permanently.
- Clear all completed tasks with a single button click.
- Your tasks are saved locally and remain even after reloading the page.

## Features:

- **Zustand for Global State:** Lightweight and scalable state management.
- **Data Persistence:** Automatically saves tasks in the browser’s localStorage.
- **Clear Completed:** Quickly remove all finished tasks from the list.
- **Minimal Boilerplate:** Simple and readable code without unnecessary complexity.
- **Efficient Rendering:** Only components using the state get re-rendered.

## Technologies:

- **React:** Component-based UI framework
- **Vite:** Lightning-fast development server and build tool
- **Zustand:** – Simplified global state solution
- **localStorage:** – For client-side data persistence

## Conclusion:

- This project demonstrates how Zustand can simplify state management in React applications. By integrating localStorage, the app ensures data persistence while maintaining clean, readable code. It serves as a great example for learning global state handling and enhancing user experience through data retention and minimal re-rendering.

## Acknowledgments:

- I would like to thank my instructor for their guidance throughout this practical task. I also appreciate the creators of Zustand for offering such an easy-to-adopt library. Their documentation and examples were extremely useful during development.