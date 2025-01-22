## Personal Financial Tracker Documentation
#  Overview:
    The Personal Financial Tracker is a web application that simplifies financial management. Built 
    with React.js, Node.js, Express.js, and MongoDB, it enables users to monitor their total 
    income, expenses, and overall balance while providing a history of recent transactions.
#  Features:
    1. Total Income
    • Displays the user's total income and allows users to add new income records with 
    details such as amount, date, and description.
    2. Total Expenses
    • Tracks the user's total expenses and Users can log expenses with attributes like 
    amount, date, category, and description.
    3. Total Balance
    • Automatically calculates the balance as: Total Balance = Total Income - Total Expenses
    4. Recent History
    • Displays recent transactions (income and expenses) with details:
    o Type (Income/Expense) , Amount , Date , Description
#  Tech Stack:
    Frontend: React.js
    • Component-Based Architecture: Reusable and modular components.
    • State Management: Efficient handling with hooks (useState, useEffect).
    • Responsive Design: Optimized for both mobile and desktop users.
    Backend: Node.js & Express.js
    • API Development: CRUD operations via RESTful APIs.
    • Middleware: Handles validation, authentication, and errors.
    • Modular Design: Scalability through structured routing and controllers.
    Database: MongoDB
    • NoSQL Database: Efficiently stores user and transaction data.
    • Schema: Contains user profile and Stores income and expenses records
#  Installation and Setup:
    Prerequisites
    • Node.js and npm installed.
    • MongoDB installed locally or access to MongoDB Atlas.
    Steps
    1. Install Dependencies:
    o Backend: cd backend then npm install
    o Frontend: cd ../frontend then npm install
    2. Setup Environment Variables:
    o Create a .env file in the backend directory:
    o PORT=5000 and MONGO_URL=<your-mongodb-connection-string>
    3. Start the Application:
    o Backend: cd backend -> npm start
    o Frontend: cd ../frontend -> npm run dev
    4. Access the Application: Navigate to http://localhost:5000 in your browser
#  Conclusion
    The Personal Financial Tracker is an intuitive tool for managing finances effectively. Its modern 
    tech stack ensures scalability and a seamless user experience. Future updates will introduce 
    more advanced features to enhance functionality.
