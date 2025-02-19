# Quiz-EZ Frontend

This is the frontend portion of the Quiz-EZ application, a quiz platform built with React. It interacts with the backend to provide a complete quiz experience.
the app is available on the link[https://quiz-mern-snowy.vercel.app/]

## Features

- **User Authentication**

  - Sign up via email with OTP verification
  - Log in effortlessly using Google OAuth
  - Secure login and logout using token-based authentication

- **Protected Routes**

  - Uses React Router along with a custom `ProtectedRoute` component to guard private pages
  - Ensures that only logged-in users can access certain features

- **Quiz Experience**

  - Enjoy dynamic quizzes with adaptive difficulty levels (easy, medium, hard)
  - Answer timed questions with automatic skip when time runs out
  - View detailed results with performance breakdowns using interactive charts (Recharts)

- **Admin Features**

  - Admins can create, update, and delete quizzes
  - Create quizzes with multiple questions, answer options, correct answers, difficulty levels, and tags

- **User Profile & History**

  - Update your profile (name, password, and profile picture)
  - Check your quiz history with detailed breakdowns of each attempt
  - See leaderboards that display the top scores

- **User Interface**
  - Modern and responsive design powered by Tailwind CSS
  - Friendly toast notifications (using react-toastify) to keep you informed

## Running the App Locally

### 1. Clone the Repository

If you haven't already, clone the repository:

```bash
git clone https://github.com/kazutokidigaya/quiz-cat.git
```

### 2. Install Dependencies

If you haven't already, clone the repository:

```bash
cd quiz-cat/frontend
npm install
```

### 3. Start the Development Server

run the following command to start the app:

```bash
npm start
```
