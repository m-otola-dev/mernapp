# mernapp
Full stack MERN app for an exercise tracker. Uses React for the UI front-end development and MongoDB, Express and Node for backend. 

** FOR THE BACKEND USING MONGODB ** 
REST API that utilized CRUD to execute the following points:
1. Create using POST /exercises
2. Read using GET /exercises
3. Update using PUT /exercises/:id
4. Delete using DELETE /exercises/:id

** FOR FRONTEND USING REACT **
UI will have 3 pages: Home page, Edit exercise page and Create exercise page.
1. Home page: will display the data for all the exercises from backend. Will get the data by called GET /exercises in the REST API. It will have an HTML table with the following properties: name, reps, weight, unit and date.
2. Edit exercise page: Lets the client edit their requested exercise. Will save the exercise by calling the PUT /exercises/:id endpoint. Will be able to take the user back to the Home page from here.
3. Create page: allows client to create a new exercise, user must add information into the five required properties. Will save the exercise in the REST API by calling the POST /exercises endpoint.
