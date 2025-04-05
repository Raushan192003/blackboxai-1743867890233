
Built by https://www.blackbox.ai

---

```markdown
# Diamond Casino

## Project Overview
Diamond Casino is an online platform that allows users to play various casino games including Teen Patti, Aviator, and Color Prediction. The application offers a user-friendly interface utilizing Tailwind CSS for styling and provides a secure environment for transactions. Players can login, register, and manage their accounts while experiencing thrilling real-time gaming.

## Installation

To set up the Diamond Casino project on your local machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/diamond-casino.git
   cd diamond-casino
   ```

2. **Install dependencies:**
   - Make sure you have Node.js and npm installed.
   - Install the necessary Node.js packages by running:
   ```bash
   npm install express mongoose bcrypt jsonwebtoken cors ws
   ```

3. **Set up MongoDB:**
   - Ensure you have MongoDB installed and running on your machine. Update the MongoDB URL in `server.js` if necessary.

4. **Start the server:**
   ```bash
   node server.js
   ```

5. **Open the application:**
   - Open your web browser and navigate to `http://localhost:3000`.

## Usage

Access the Diamond Casino app through the index.html file:
1. **Register:** Create a new account by providing an email and password.
2. **Login:** Use your credentials to log in.
3. **Play Games:** Choose from available games and place bets with user balance.
4. **Manage Account:** Update account details and view transaction history.

## Features
- User Authentication: Sign up and log in securely
- Multiple Games: Play Teen Patti, Aviator, Color Prediction, and more
- Real-time Notifications: Get updates and results directly on the platform
- Responsive Design: A mobile-friendly, attractive user interface
- Secure Transactions: Ensure player data and transactions are safe
- Maintain your game history and transaction history

## Dependencies
The project uses the following key libraries included in `package.json`:
- **Express:** Web framework for Node.js
- **Mongoose:** MongoDB ORM for data modeling
- **Bcrypt:** Password hashing library
- **Jsonwebtoken:** Library for JWT-based authentication
- **Cors:** Middleware for enabling CORS
- **Ws:** WebSocket library for real-time communication

## Project Structure
The project is organized as follows:

```
diamond-casino/
├── index.html          # Main landing page
├── lobby.html          # Game lobby for selecting games
├── register.html       # Registration page
├── login.html          # Login page
├── teen-patti.html     # Teen Patti game page
├── aviator.html        # Aviator game page
├── color-prediction.html# Color Prediction game page
├── script.js           # JavaScript for front-end functionality
├── server.js           # Express server logic and API routes
└── package.json        # Project metadata and dependencies
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

For more information and updates, please check the project's GitHub repository.
```