# CodeAlpha_Social_Platform

## Project Description
This repository contains the source code for the "CampusLoop" Social Media Platform, a full-stack web application developed during the CodeAlpha Virtual Internship Program in Full Stack Development. The project features interactive community feeds, dynamic user profile avatars, and a real-time search interface designed specifically for students.

## Features
*   **Interactive Community Feed:** Users can view, create, and interact with posts within the campus community.
*   **Premium Navigation Interface:** A responsive and modern navigation bar for seamless user experience.
*   **Real-time Search:** Search functionality to find posts, circles, or other students quickly.
*   **Dynamic User Profiles:** Integration of dynamic user avatars and personalized greetings.
*   **Authentication & Session Management:** Secure login and logout capabilities handling user sessions.

## Technologies Used
*   **Frontend:** HTML5, CSS3, JavaScript (ES6+), DOM Manipulation
*   **Backend:** Node.js, Express.js (middleware and routing configuration)
*   **Database:** SQLite (`campusloop.db`)
*   **Development Tools:** Visual Studio Code (IDE), Git

## Setup and Installation
To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [repository_url]
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd CodeAlpha_Social_Platform
    ```
3.  **Install backend dependencies:**
    Ensure you have Node.js installed. Then, install the required packages using npm:
    ```bash
    cd server
    npm install
    ```
4.  **Configure Environment Variables:**
    Create a `.env` file in the `server` directory (you can use `.env.example` as a template) and add your environment-specific configurations.
5.  **Initialize the Database:**
    The SQLite database (`campusloop.db`) is located in the `server/data` directory. Ensure the server has read/write access to this file.
6.  **Start the Server:**
    ```bash
    npm start
    ```
7.  **Access the Application:**
    Open your web browser and navigate to `http://localhost:[port]` (typically `http://localhost:3000` or the port specified in your `.env` file).

## Project Structure
```text
CodeAlpha_Social_Platform/
├── public/             # Frontend assets (HTML, CSS, client-side JS, images)
│   ├── css/            # Stylesheets
│   ├── images/         # Image assets
│   ├── js/             # Client-side JavaScript logic (auth.js, feed.js, etc.)
│   ├── index.html      # Landing page
│   ├── feed.html       # Main social feed interface
│   └── ...
├── server/             # Backend Node.js/Express server
│   ├── data/           # SQLite database directory
│   ├── middleware/     # Custom Express middleware
│   ├── node_modules/   # Node.js dependencies
│   ├── routes/         # API route definitions
│   ├── db.js           # Database connection and queries
│   ├── server.js       # Main server entry point
│   └── package.json    # Backend project metadata and dependencies
└── README.md           # Project documentation
