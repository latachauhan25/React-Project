# Technology Stack
Frontend: React.js (Hooks: useState, useEffect)
Routing: react-router-dom
Styling: Custom CSS (App.css)
Backend (Mock API): JSON Server (db.json)
API Type: RESTful API
Port: localhost:8000

## Application Workflow (CRUD Operations)
1. Read (View Students)
Component: StudentTable.js
Fetches student data using useEffect()
Displays records dynamically in a table
Provides View, Edit, Delete actions per row

2. Create (Add Student)
Component: CreateStudent.js
Form-based input system
Sends POST request to API
Includes client-side validation

3. Update (Edit Student)
Component: EditStudent.js
Uses useParams() to get student ID
Pre-fills form with existing data
Sends PUT request to update record

4. Delete (Remove Student)
Function: RemoveDetails
Confirmation dialog via window.confirm
Sends DELETE request
Updates UI instantly




