# Real-Time Stock Portfolio Tracker

## Overview
The Real-Time Stock Portfolio Tracker is an application designed to help users manage their stock investments by tracking performance, analyzing stocks, and providing real-time updates on stock prices.

## Architecture
This application follows a microservices architecture with the following components:
- **Frontend:** A user-friendly interface built with React.js for creating and managing portfolios.
- **Backend:** Node.js and Express for API handling and business logic.
- **Database:** MongoDB to manage user data and stock information.
- **Websocket Service:** For real-time data updates.

## Setup Instructions
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/rajvardhan75/Devops-Mini.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd Devops-Mini
   ```

3. **Install Dependencies:**
   For both frontend and backend:
   ```bash
   npm install
   ```

4. **Set Up Environment Variables:**
   Create a `.env` file in the root directory and provide the necessary configurations:
   ```bash
   PORT=5000
   DB_URI=your_database_uri
   ```

5. **Run the Application:**
   For backend:
   ```bash
   node server.js
   ```
   For frontend, navigate to the frontend directory and run:
   ```bash
   npm start
   ```

6. **Access the Application:**
   Open your web browser and go to `http://localhost:5000`.

By following these steps, you will have a fully functional Real-Time Stock Portfolio Tracker.