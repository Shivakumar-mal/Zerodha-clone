# Zerodha


Full-Stack Stock Trading Platform
This project replicates a stock trading platform inspired by Zerodha's dashboard, designed for learning and demonstration purposes. It simulates trading functionalities and provides a user-friendly interface to manage holdings, positions, and orders.

🔧 Features
📈 Dashboard UI: A user interface inspired by Zerodha's trading dashboard, displaying user holdings, positions, and active orders.

🔐 User Holdings & Positions: View current stock holdings, positions, and their value.

⚙️ Backend RESTful APIs: Built with Node.js and Express to handle user authentication, orders, and stock data.

🗃️ MongoDB Integration: Utilizes MongoDB with Mongoose schemas to store user data, orders, and stock information.

🎯 Responsive Design: Developed using React.js for the frontend, ensuring a seamless experience across devices.

🛠️ Tech Stack
Frontend: React.js, HTML, CSS, JavaScript

Backend: Node.js, Express

Database: MongoDB, Mongoose

Version Control: Git & GitHub

Install Dependencies
Install Frontend dependencies:

bash
Copy
Edit
cd frontend
npm install


Install Backend dependencies:

bash
Copy
Edit
cd backend
npm install


Set Up Environment Variables
Create a .env file in the backend folder with the following configuration:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
PORT=5000


Start the Application

Frontend:
bash
Copy
Edit
cd frontend
npm start


Backend:
bash
Copy
Edit
cd backend
npm start

