# AI Resume Analyzer

A modern, AI-powered web application that analyzes resumes to provide actionable feedback, ATS scores, and improvement tips. Built with the latest web technologies including React 19, React Router 7, and Puter.js.

## 🚀 Features

- **Smart Resume Analysis**: Upload your PDF resume and get instant, AI-driven feedback tailored to your job goals.
- **ATS Scoring**: Receive an estimated Applicant Tracking System (ATS) score to understand how well your resume parses.
- **Actionable Insights**: Get specific, detailed suggestions on how to improve your resume's content, formatting, and impact.
- **Visual Preview**: Automatically converts your PDF resume into an image for easy viewing within the app.
- **Secure Cloud Storage**: Leverages [Puter.js](https://puter.com) for secure file storage and data persistence.
- **Modern UI/UX**: A sleek, responsive interface built with Tailwind CSS 4 and React Router 7.

## 🛠️ Tech Stack

- **Frontend Framework**: [React 19](https://react.dev/)
- **Routing**: [React Router 7](https://reactrouter.com/)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
- **Backend & AI**: [Puter.js](https://docs.puter.com/) (Cloud FS, Key-Value Store, AI Chat)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **State Management**: [Zustand](https://github.com/pmndrs/zustand)
- **PDF Processing**: `pdfjs-dist`

## 📋 Prerequisites

- **Node.js**: Version 20 or higher is recommended.
- **Puter Account**: You will need a [Puter.com](https://puter.com) account to use the backend features (Sign-up is free and handled within the app).

## 📦 Installation

1.  **Clone the repository**
    ```bash
    git clone <repository-url>
    cd ai-resume-analyzer-main
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

## 🏃‍♂️ Running the App

1.  **Start the development server**
    ```bash
    npm run dev
    ```

2.  **Open the application**
    Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal).

3.  **Authentication**
    When you first use the app, you will be prompted to sign in to your Puter.com account. This is required to enable file uploads, storage, and AI analysis features.

## 📂 Project Structure

- `app/routes`: Contains the application routes (Home, Auth, Upload, Resume View).
- `app/components`: Reusable UI components (Navbar, FileUploader, Analysis displays).
- `app/lib`: Utility functions and Puter.js integration logic.
- `app/constants`: Static data and prompt templates.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
