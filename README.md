draft 

-----

# 🚀 Task Master - Advanced Task Management Application

Task Master is a modern, feature-rich task management application built with **React** and **Tailwind CSS**. This application provides a comprehensive solution for organizing personal and professional tasks with advanced filtering, categorization, and real-time statistics.

This is a full-featured **CRUD** (Create, Read, Update, Delete) application designed to help users efficiently manage their daily tasks. The application offers an intuitive interface with powerful features including priority-based task organization, category management, status tracking, and advanced search capabilities.

*This project was developed as part of the **IBM Student Developer Initiative Capstone Project**, showcasing the integration of AI-assisted development tools to accelerate and optimize the development process.*

## 📍 Live Demo

[**View the live application here**](https://your-live-demo-link.com)

## 📸 Application Preview

*Add a GIF demo or several screenshots here (blm jadi*

| Desktop View | Mobile View |
| <img width="707" height="476" alt="image" src="https://github.com/user-attachments/assets/bec54833-b70f-4db2-a310-a03d0c3e77f4" />
 | :---: |
|  |  |

-----

## ✨ Key Features

### 📊 Core & Advanced Functionality

  * **Full CRUD Operations:** Create, Read, Update, and Delete tasks with comprehensive details (title, description, category, priority, due date, and status).
  * **Real-time Statistics Dashboard:** Live counters showing **Total Tasks**, **Pending**, **In-Progress**, and **Completed** tasks.
  * **Advanced Search:** Full-text search across task titles and descriptions.
  * **Multi-level Filtering:** Filter tasks by:
      * **Status** (pending/in-progress/completed)
      * **Priority** (low/medium/high)
      * **Category** (personal/work/shopping/health/other)
  * **Data Persistence:** Uses the `sessionStorage` API to save tasks, so data persists even after a page refresh.
  * **Quick Status Toggle:** Click the circle icon to quickly cycle through task statuses (Pending ➔ In-Progress ➔ Completed).

### 🎨 User Experience (UX) & Interface

  * **Visual Priority System:** Color-coded badges for instant priority recognition:
      * 🔴 **High Priority**
      * 🟡 **Medium Priority**
      * 🟢 **Low Priority**
  * **Fully Responsive Design:** Optimized layouts for desktop, tablet, and mobile devices.
  * **Form Validation:** Required field validation with user-friendly error messages.
  * **Confirmation Dialogs:** Prevents accidental deletions with a confirmation prompt.
  * **Empty State Handling:** Helpful messages when no tasks exist or filters return no results.
  * **Interactive UI:** Smooth transitions, hover effects, and a clean visual hierarchy.

-----

## 🛠️ Technologies & Tools Used

| Category | Technology |
| :--- | :--- |
| **Framework & Libraries** | React 18 (Hooks: `useState`, `useEffect`), Vite |
| **Styling** | Tailwind CSS, Lucide React (Icons) |
| **Data Management** | SessionStorage API, React Hooks |
| **Development Tools** | Node.js, npm, ESLint, VS Code |
| **Version Control** | Git & GitHub |
| **Deployment Platforms** | Netlify, Vercel, GitHub Pages |

-----

## ⚙️ Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) (which includes npm) installed on your machine.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
2.  **Navigate into the project directory:**
    ```bash
    cd your-repo-name
    ```
3.  **Install NPM packages:**
    ```bash
    npm install
    ```
4.  **Run the development server (Vite):**
    ```bash
    npm run dev
    ```
5.  Open [http://localhost:5173](https://www.google.com/search?q=http://localhost:5173) (or the port specified in your console) to view it in the browser.

-----

## 🌍 Deployment

This application is built as a static site and can be easily deployed to any static site hosting service such as:

  * Netlify
  * Vercel
  * GitHub Pages

-----

## 📜 License

Distributed under the MIT License. See the `LICENSE` file for more information.
