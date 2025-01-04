Prerequisites
Before you start, you need to have the following installed:

Node.js (v14 or higher) - Download Node.js
MongoDB - Either install MongoDB locally or use a cloud database like MongoDB Atlas.
Git (Optional) - To clone the repository.
Steps to Run the App
1. Clone the Repository
Clone the project to your local machine:

bash
Copy code
git clone https://github.com/ManishVerma4903/W3villa_project.git
cd mern-app
2. Install Backend Dependencies
Navigate to the backend folder and install dependencies:

bash
Copy code
cd backend
npm install

3. Install Frontend Dependencies
Now, install the frontend dependencies:

bash
Copy code
cd ../W3villa
npm install
4. Set Up MongoDB
If you're using MongoDB Atlas, get your connection string.
If you're using local MongoDB, ensure it's running by starting the MongoDB service:
bash
Copy code
mongod
5. Configure Environment Variables
Backend
In the backend folder, create a .env file with:

env
Copy code
MONGO_URI=mongodb://<your_mongo_connection_string>
PORT=5000
JWT_SECRET=<your_jwt_secret>
Frontend
In the frontend folder, create a .env file with:

env
Copy code
REACT_APP_API_URL=http://localhost:5000
6. Run the App
Start Backend (Server)
Go to the backend folder and start the server:

bash
Copy code
cd backend
npm start
Start Frontend (React App)
Go to the frontend folder and start the frontend:

bash
Copy code
cd frontend
npm start
7. Open the App
