# Realfy Posture App – Frontend

This is the frontend code for the Realfy Posture App, which analyzes user posture from videos and flags bad posture in real time.

---

## 🔗 How It Works (Frontend + Backend Workflow)

- The user records a short video of themselves using the web app’s recording feature.
- The frontend sends the recorded video to the backend via an HTTP POST request.
- The backend:
  - Receives the video
  - Processes video frames with Mediapipe to detect body landmarks
  - Analyzes posture angles
  - Flags any bad posture
  - Sends a JSON response with posture analysis
- The frontend:
  - Displays the results to the user
  - Shows whether posture is good or bad


## 🚀 Tech Stack Used

- **React.js** (Vite / CRA)
- **Material UI** (MUI)
- **Recharts** (charting)
- **Fetch API** (for backend communication)

---

## 🛠 Setup Instructions (Run Locally)

1. Clone the repository:
    ```
    git clone https://github.com/soumyajit73/realfy-posture-app_frontend
    ```

2. Install dependencies:
    ```
    npm install
    ```

3. Start the development server:
    ```
    npm start
    ```

4. Open your browser at:
    ```
    http://localhost:3000
    ```

> **Important:**  
> Make sure your backend server is running locally or update the API URL in your frontend code to point to your deployed backend endpoint.

---

## 🌐 Deployed Frontend App

https://realfy-posture-app-frontend.vercel.app/

---

## 🎥 Demo Video

https://drive.google.com/drive/folders/1ntz97dV1T0pvDuvKzlhxmjId_-9wDavZ?usp=drive_link

---
