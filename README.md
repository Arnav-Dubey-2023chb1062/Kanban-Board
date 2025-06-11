# Kanban Board

A retro-themed Kanban board application built with **React**, **TypeScript**, **TailwindCSS**, and **Vite**. Implements interactive task management with real-time backend synchronization.

---

## Features

- **Drag-and-Drop Interface**
  - Utilizes the HTML5 Drag and Drop API to allow seamless movement of tasks between columns: **Todo**, **In Progress**, and **Done**.
- **Priority-Based Styling**
  - Tasks are visually differentiated by color and icon (blue for low, yellow for medium, red for high priority) using TailwindCSS utility classes.
- **Story Point System**
  - Tasks are assigned points following the Fibonacci sequence (0, 1, 2, 3, 5, 8, 13, 21), with interactive controls for incrementing and decrementing points.
- **Retro UI Design**
  - Features a pixel-inspired interface with the “Press Start 2P” Google Font for a nostalgic gaming aesthetic.
- **Responsive Layout**
  - Fully adaptive design for desktop and mobile devices, leveraging TailwindCSS’s responsive utilities.
- **Real-Time Data Synchronization**
  - Tasks are fetched from and updated to a RESTful backend API, supporting CRUD operations.
- **Inline Task Editing**
  - Click-to-edit functionality for task titles, with save and cancel options for user convenience.

---

## Technologies

- **React** (v18+): Component-based UI framework
- **TypeScript**: Static typing for improved code quality
- **TailwindCSS** (v3+): Utility-first CSS framework
- **Vite**: Fast build tool for modern web applications
- **HTML5 Drag and Drop API**: Native browser support for drag-and-drop interactions
- **RESTful API Integration**: HTTP requests for task management

---

## Prerequisites

- **Node.js**: v16 or higher
- **npm**: v8 or higher
- **Backend API**: (Optional) Endpoint for task CRUD operations

---

## Installation

1. **Clone the repository:**
2. 2. **Install dependencies:**
3. **Configure API endpoint:**
- Set the backend API URL in the appropriate configuration file or environment variable.
4. **Start the development server:**

