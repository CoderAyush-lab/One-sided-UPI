# Banking App

## Overview
This is a simple web-based banking application that allows users to log in, manage their balance, and track transaction history. The application features user authentication, balance updates, and transaction storage using `localStorage`.

## Features
- **User Authentication**: Users can log in with predefined credentials.
- **Balance Management**: Users can add or deduct money from their balance.
- **Transaction History**: A history of all transactions is stored and displayed.
- **Local Storage**: All user data is stored in `localStorage` to persist between sessions.
- **Logout Functionality**: Users can log out to prevent unauthorized access.

## File Structure
```
📂 BankingApp
├── 📜 index.html       # Login Page
├── 📜 user.html        # User Dashboard
├── 📜 history.html     # Transaction History Page
└── 📜 README.md        # Project Documentation
```

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/banking-app.git
   ```
2. Navigate to the project folder:
   ```bash
   cd banking-app
   ```
3. Open `index.html` in a browser to use the app.

## Usage
1. **Login** using the following credentials:
   - **User**: `user1` / `10814`
2. Once logged in:
   - View your balance on `user.html`.
   - Add or deduct money with a reason.
   - View transaction history on `history.html`.
   - Log out to end the session.

## Future Improvements
- **Database Integration**: Replace `localStorage` with a backend database.
- **User Registration**: Allow new users to sign up.
- **Enhanced Security**: Implement encryption and authentication improvements.
- **Mobile Responsiveness**: Improve UI for better mobile experience.

## License
This project is open-source and available under the [MIT License](LICENSE).

