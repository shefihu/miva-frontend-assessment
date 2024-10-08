# Student Management System

This project is a web-based Student Management System built with Next.js.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Install dependencies:

   ```
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory with the following format:

   ```
   NEXTAUTH_SECRET="your_secret_here"
   MONGODB_URI="your_mongodb_uri_here"
   ```

   Note: You'll need to register for MongoDB Atlas to get a connection URI.

4. Force install dependencies (if needed):
   ```
   npm install --force
   ```

## Features

- User Authentication:

  - Register
  - Login

- Student Management:
  - Create new student records
  - Edit existing student information
  - Delete student records
  - View student details

## Running the Application

To start the development server:
Visit `http://localhost:3000` in your browser to use the application.

## Technologies Used

- Next.js
- MongoDB
- NextAuth.js for authentication

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
