Certainly! Here’s the full README with the **MERN** tech stack included:

---

# HackerRank Clone

This project is a clone of the popular coding platform [HackerRank](https://www.hackerrank.com/) built from scratch. It aims to recreate the user interface and core functionalities of HackerRank, including features for solving coding challenges, viewing submissions, and user authentication.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **User Authentication:** Register and log in to access coding challenges.
- **Challenge Management:** View, solve, and submit coding challenges.
- **Code Editor:** Embedded code editor with syntax highlighting and language support.
- **Test Case Execution:** Run code against predefined test cases.
- **Leaderboard:** See top users based on challenge completions and performance.

## Demo

[Include a link to a live demo or screenshots if available.]

## Tech Stack

This project is built using the **MERN** stack:

- **MongoDB:** For storing user data, challenges, and submissions.
- **Express:** Backend framework for building the RESTful API.
- **React:** Frontend library for building the user interface.
- **Node.js:** Server environment for running the backend application.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/hackerrank-clone.git
   cd hackerrank-clone
   ```

2. **Install dependencies:**
   ```bash
   # Frontend
   cd client
   npm install

   # Backend
   cd ../server
   npm install
   ```

3. **Set up environment variables:**
   - Create a `.env` file in the `server` folder and add your environment variables:
     ```plaintext
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

4. **Run the application:**
   ```bash
   # Start backend server
   cd server
   npm start

   # Start frontend
   cd ../client
   npm start
   ```

5. **Access the application:**
   Open your browser and go to `http://localhost:3000`.

## Usage

1. Sign up or log in to your account.
2. Browse and select a coding challenge.
3. Write and submit your code using the code editor.
4. View your score and the leaderboard for each challenge.

## Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

Feel free to reach out if you have questions or need any support. Happy coding!

---

This README now includes the **MERN** stack description and is formatted to display correctly on GitHub!
