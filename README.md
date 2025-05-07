1. Clone the Repository
First, clone the project repository from GitHub to your local machine.

bash
Copy
Edit
git clone https://github.com/Biplab96Das/Task-Manager.git
2. Navigate to the Project Directory
Once the repository is cloned, navigate into the project folder.

bash
Copy
Edit
cd Task-Manager
3. Install Node.js
Make sure Node.js is installed on your system. You can check by running:

bash
Copy
Edit
node -v
If it’s not installed, download and install Node.js from the official website: Node.js Official Website.

4. Install Dependencies
This project requires various npm dependencies (like Angular, Bootstrap, etc.). To install these, run the following command inside the project directory:

bash
Copy
Edit
npm install
This will install all the necessary dependencies listed in the package.json file.

5. Serve the Application Locally
Now that all dependencies are installed, you can run the application using the Angular CLI:

bash
Copy
Edit
ng serve
This will start the Angular development server. The application will be available at http://localhost:4200 by default.

6. Open the Application in Your Browser
Open your browser and go to:

arduino
Copy
Edit
http://localhost:4200
You should see the Task Manager application running locally.

7. (Optional) Build for Production
If you want to create a production build of the application, use the following command:

bash
Copy
Edit
ng build --prod
This will create a production-ready build in the dist/ folder, optimized for performance. You can then deploy it to a web server.

8. Using the Application
Adding Tasks: You can create new tasks by filling in the title, description, due date, and priority.

Editing Tasks: Click the "Edit" button next to a task to modify its details.

Deleting Tasks: Remove tasks by clicking the "Delete" button next to each one.

Changing Task Status: You can mark tasks as "Completed" or "Pending" by clicking on the appropriate buttons.

Dark Mode: Toggle between dark and light modes by clicking the sun/moon icon.

Filtering Tasks: Filter tasks by their status using the dropdown menu.

Due Date Search: You can search tasks by their due date using the search input.
