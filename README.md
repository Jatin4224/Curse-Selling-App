# Curse-Selling-App
**Documentation for Course Selling App**

## Course Selling App

The Course Selling App is a web application built using the MERN stack, designed to provide a platform for selling and purchasing online courses. The app allows administrators to create and manage courses, while users can browse, purchase, and access their purchased courses.

### Features

1. **Admin Panel**
   - Admins can sign up with a unique username, email, and password.
   - Once logged in, admins have access to a dedicated admin panel.
   - Admins can create new courses by providing a title, description, price, and an image link for the course thumbnail.
   - Courses can be published or unpublished as per the admin's preference.
   - Admins can edit existing courses to update their details.

2. **User Authentication**
   - Users can sign up for the platform using a username, email, and password.
   - Registered users can log in to access the full features of the app.

3. **Course Purchase**
   - Authenticated users can purchase courses they are interested in.
   - Secure payment gateway integration ensures safe transactions.

4. **Course Management**
   - Users can view all available courses on the platform, whether they are registered or not.
   - Users can access their purchased courses from their profile.

### Getting Started

To run the Course Selling App locally, follow the steps below:

1. Clone the repository:
   ```
   git clone https://github.com/your-username/course-selling-app.git
   ```

2. Navigate to the project directory:
   ```
   cd course-selling-app
   ```

3. Install dependencies for the server and the client:
   ```
   cd server && npm install
   cd ../client && npm install
   ```

4. Set up environment variables:
   - Create a `.env` file in the `server` directory and provide the necessary configurations, such as the database connection URI, payment gateway credentials, etc.

5. Start the development server:
   ```
   cd ../server && npm start
   ```

6. Start the client:
   ```
   cd ../client && npm start
   ```

7. The app should now be running at `http://localhost:3000/`.

### Technologies Used

- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MongoDB
- Payment Gateway: []

