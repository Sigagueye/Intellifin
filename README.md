# IntelliFin - Intelligent Financial Optimization Dashboard

[![Status](https://img.shields.io/badge/status-beta-orange.svg)]() [![License](https://img.shields.io/badge/License-Proprietary%20EULA-red.svg)](EULA.md)

**IntelliFin** is an interactive web dashboard for visualizing and simulating financial optimization strategies using AI-driven models. This application is currently in a **beta phase** and is based on ongoing research by Saga Ndeye.

**Important:** Use of this software is governed by the terms set forth in the **End-User License Agreement (EULA)** included in this repository.

## Features

-   **Optimization Hub:** Visualize a Genetic Algorithm's optimization path, view AI-powered recommendations, and analyze strategic options in the Decision Matrix.
-   **Predictive Platform:** Interactively adjust marketing spend to see real-time AI predictions on ROI, CAC, and conversions.
-   **Simulation Ecosystem:** Run "what-if" scenarios using different strategic models against market volatility.
-   **Competitive Analysis:** Simulate market share and Share of Voice (SOV) based on budget allocations.
-   **Data Management:** A dedicated portal for API access and CSV data uploads.

## Tech Stack

-   **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES Modules)
-   **Build Tool:** [Vite](https://vitejs.dev/)
-   **Charting Library:** [Chart.js](https://www.chartjs.org/)
-   **Development:** Node.js, npm, ESLint, Prettier

## Project Structure

The project follows a modern structure, separating source code from distribution files.

/intellifin-dashboard
├── dist/                # Production build output
├── src/                 # Source code
│   ├── assets/
│   ├── css/
│   ├── js/
│   │   ├── api.js
│   │   └── main.js
│   └── index.html
├── .gitignore
├── EULA.md              # Your End-User License Agreement
├── index.html           # Root redirect to src (for some hosts)
├── package.json
├── vite.config.js
└── README.md


## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

You must have [Node.js](https://nodejs.org/) (version 18 or higher) and npm installed.

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/intellifin-dashboard.git](https://github.com/your-username/intellifin-dashboard.git)
    cd intellifin-dashboard
    ```

2.  **Install dependencies:**
    This command reads the `package.json` file and downloads all the necessary tools (like Vite and Chart.js).
    ```sh
    npm install
    ```

### Running the Application

1.  **Start the development server:**
    This command starts the Vite development server with Hot Module Replacement (HMR) for a smooth development experience.
    ```sh
    npm run dev
    ```
    Your application will be available at `http://localhost:5173` (or the next available port).

2.  **Build for production:**
    When you are ready to deploy, run this command:
    ```sh
    npm run build
    ```
    Vite will bundle and optimize all your files into the `/dist` directory. You can then deploy the contents of this folder to any static web host.

## Author

* **Siga Ndeye** - *Initial Research & Development*# Intellifin
