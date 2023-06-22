# Mid-Exam

Step 1: Set up the project

1. Create a new directory for your project.
2. Open a command prompt or terminal and navigate to the project directory.
3. Initialize a new Node.js project by running the following command
4. Install the required dependencies by running the following command

Step 2: Set up the Express app and create the server file

1. Create a new JavaScript file, for example, server.js, in your project directory.
2. Open server.js in a code editor.
3. Import the required modules at the top of the file
4. Create an instance of the Express app
5. Set up middleware to parse JSON data and handle URL-encoded data
6. Define the MongoDB connection URL and establish the database connection:
7. Start the server and listen on a specific port

 Step 3: Create routes for CRUD operations

1. Create a new directory in your project directory, for example, routes.
2. Inside the routes directory, create a new JavaScript file, for example, students.js.
3. Open students.js in a code editor.
4. Import the required modules at the top of the file:
5. Define routes for CRUD operations:
6. Export the router at the end of the file:

Step 4: Connect routes to the Express app

1. Open app.js in a code editor.
2. Import the student routes at the top of the file
3. Connect the student routes to the Express app

Step 5: Implement the logic for CRUD operations

1. Create a new directory in your project directory, for example, models.
2. Inside the models directory, create a new JavaScript file, for example, student.controllers.js.
3. Open student.models.js in a code editor.
4. Define the schema for the student model using Mongoose:
5. Implement the logic for CRUD operations in students.js using the Mongoose model defined in student.routes.js.

Step 6: Test the API

1. Start the server by running the following command in the project directory
2. Use a tool like Postman or cURL to test the API endpoints for CRUD operations on the student database.
3. Create a new student: Send a POST request to http://localhost:3000/students with the student data in the request body.
4. Get all students: Send a GET request to http://localhost:3000/students.
5. Get a single student by ID: Send a GET request to http://localhost:3000/students/:id where :id is the ID of the student.
6. Update a student by ID: Send a PUT request to http://localhost:3000/students/:id where :id is the ID of the student, with the updated student data in the request body.
7. Delete a student by ID: Send a DELETE request to http://localhost:3000/students/:id where :id is the ID of the student.
