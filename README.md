# Smart Hub for College Management System Using MERN Stack

Smart Hub is an ERP-based web application designed using the MERN stack (MongoDB, Express.js, React.js, and Node.js) to streamline and optimize academic and administrative processes in colleges. This system simplifies college management, enhances communication, and boosts productivity across the academic ecosystem.

---

## Features

### For Admin:

- **Dashboard**: Overview of college activities and statistics.
- **User Management**: Add, update, and remove students and teachers.
- **Task Management**: Assign tasks and monitor progress.
- **Reports and Analytics**: View detailed reports on college activities.

### For Teachers:

- **Dashboard**: Manage classes, tasks, and assignments.
- **Task Manager**: Assign and evaluate assignments.
- **Attendance Tracking**: Record and manage student attendance.

### For Students:

- **Dashboard**: Access class schedules, assignments, and grades.
- **Placement Preparation**: Study materials for aptitude and coding.
- **Task Manager**: Track and submit assignments.
- **Help Chatbot**: Get assistance for queries and issues.

---

## Output
![Image](https://github.com/user-attachments/assets/c970517e-407a-4aea-a26d-f40b2aae51dd)
![Image](https://github.com/user-attachments/assets/0dd03ee9-c104-4275-a700-6aa91b0214e6)
![Image](https://github.com/user-attachments/assets/a384f3d5-495b-4d98-9a67-c1e8cde548e2)
![Image](https://github.com/user-attachments/assets/39d08496-c041-4c0d-ba61-ac8e03c777ef)
![Image](https://github.com/user-attachments/assets/8d6dc725-1dae-4801-984d-8db6dcfda06a)


## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT) for secure access control
- **Hosting**: Netlify (Frontend), Heroku/AWS (Backend)

---

## Installation and Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/smart-hub-college-management.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd smart-hub-college-management
   ```

3. **Install dependencies:**

   - Backend:
     ```bash
     cd backend
     npm install
     ```
   - Frontend:
     ```bash
     cd frontend
     npm install
     ```

4. **Environment Variables:**
   Create a `.env` file in the backend directory and add the following:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```

5. **Run the application:**

   - Backend:
     ```bash
     npm run dev
     ```
   - Frontend:
     ```bash
     npm start
     ```

6. **Access the application:**
   Open your browser and navigate to `http://localhost:3000`.

---

## Folder Structure

```
smart-hub-college-management/
|-- backend/
|   |-- models/
|   |-- routes/
|   |-- controllers/
|   |-- server.js
|
|-- frontend/
|   |-- src/
|       |-- components/
|       |-- pages/
|       |-- App.js
|-- README.md
```

---

## Contributing

Contributions are welcome! If you'd like to contribute:

1. Fork the repository.
2. Create a new branch for your feature.
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push the branch.
   ```bash
   git commit -m "Add your message here"
   git push origin feature-name
   ```
4. Open a Pull Request.

---

## Acknowledgments

- **MongoDB** for database management.
- **React** for the interactive UI.
- **Node.js and Express.js** for backend services.
- **Tailwind CSS** for modern and responsive design.

---

## Contact

If you have any questions or suggestions, feel free to reach out at rsaisusanth@gmail.com.


