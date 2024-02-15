**Testing Steps:**

**FIRST install all the dependencies**
   - `npm install` in the project directory.

1. **Start Server:**
   - Execute `npm start` or `nodemon app.js` in the project directory.

2. **Open Postman:**
   - Launch the Postman application.

3. **Test Endpoints:**
   - **Login Endpoint:**
     - Method: POST
     - URL: `http://localhost:3000/auth/login`
     - Body (JSON): `{"username": "Amulya", "password": "Demo1"}`

   - **Register Endpoint:**
     - Method: POST
     - URL: `http://localhost:3000/auth/register`
     - Body (JSON): `{"username": "Amulyas", "password": "hi"}`

   - **Create New Blog:**
     - Method: POST
     - URL: `http://localhost:3000/blogs`
     - Body (JSON): `{"authorId":1,"title": "The Lightening Theif", "content": "The Lightning Thief is the first novel in Rick Riordan's....."}`

   - **Retrieve All Blogs:**
     - Method: GET
     - URL: `http://localhost:3000/blogs`

   - **Retrieve Blog by Author ID:**
     - Method: GET
     - URL: `http://localhost:3000/blogs/{authorId}`
