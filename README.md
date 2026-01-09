# HR Analytics Dashboard

### **Built by [Mahmoud Hamdy](https://www.linkedin.com/in/mahmoudhamdymahmoud/)**

A professional-grade, interactive HR Analytics Dashboard designed to visualize workforce demographics, compensation equity, and absence trends. This project demonstrates full-stack data capabilities, from offline data processing (Python) to a responsive, client-side web application (React/Vite).

## 🚀 Key Features

*   **Executive Summary**: High-level KPIs driven by real-time data analysis (Attrition, Salary, Headcount Risk).
*   **Workforce Analytics**: Interactive charts showing attrition by tenure, hiring velocity, and generational demographics.
*   **Compensation Module**: Deep dive into salary distributions, gender pay gap analysis, and cost-of-attrition modeling.
*   **Absence Tracking**: Heatmaps and Bradford Factor analysis to identify burnout risks.
*   **Performance & Talent**: 9-Box grid and performance vs. salary scatter plots for talent management.
*   **Data Manager**: 
    *   Full CRUD capabilities for Employee and Absence records.
    *   **Auto-Calculated Salaries**: Automatically splits gross salary into components (Basic, Housing, Transport, Tax, etc.).
    *   **Local Persistence**: Changes are saved to the browser's Local Storage, surviving page reloads.

## 🛠️ Technologies Used

*   **Frontend Framework**: React 18 + Vite
*   **Language**: TypeScript
*   **Styling**: Custom CSS (Dark/Light Mode aware), Lucide React (Icons)
*   **Visualization**: Recharts
*   **Data Processing**: PapaParse (CSV Parsing), Python (Data Generation)
*   **State Management**: React Context API & Local Storage

## 📂 Project Structure

*   **/analysis**: Python scripts for generating and processing the initial mock datasets (ETL pipeline).
*   **/site**: The main React application.
    *   **src/pages**: Individual dashboard views (Home, Workforce, Compensation, etc.).
    *   **src/utils/dataLoader.ts**: Handles CSV parsing and local storage logic.
    *   **public/data**: Stores the raw CSV files serving as the initial database.

## 🏁 Getting Started

### Prerequisites
*   Node.js (v18+)
*   npm

### Installation
1.  Clone the repository:
    ```bash
    git clone https://github.com/mahmoudhmahmoud/hr-analytics-dashboard.git
    ```
2.  Navigate to the site directory:
    ```bash
    cd site
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```
4.  Start the development server:
    ```bash
    npm run dev
    ```

## 👤 Author

**Mahmoud Hamdy**

*   **LinkedIn**: [https://www.linkedin.com/in/mahmoudhamdymahmoud/](https://www.linkedin.com/in/mahmoudhamdymahmoud/)
*   **GitHub**: [@mahmoudhmahmoud](https://github.com/mahmoudhmahmoud)

---
*© 2026 Mahmoud Hamdy. All rights reserved.*
