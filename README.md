# Student Management System (React Frontend)

Basic CRUD frontend using React, React Router DOM and Axios.

## Run

    npm install
    npm run dev

Open http://localhost:5173

## Backend URL

Edit `src/api.js` and change `baseURL` to your backend address.
Your backend must allow CORS for http://localhost:5173.

## Student fields

id (auto), name, email, rollNo, subject
To change the fields, edit `StudentForm.jsx`, `StudentList.jsx` and `StudentView.jsx`.

## Routes

| Path        | Page          |
|-------------|---------------|
| /           | All students  |
| /add        | Add student   |
| /edit/:id   | Edit student  |
| /view/:id   | View student  |
