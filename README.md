# Missing Letter Game - PHP Web Application

A complete web-based game application where users guess missing letters in words to score points. Built with PHP, MySQL, and vanilla CSS.

## 🌟 Features

### User Features
- **User Registration & Authentication** - Secure user registration and login system
- **Profile Management** - Personal profiles with game statistics
- **Missing Letter Game** - Interactive word game where players guess missing letters
- **Score Tracking** - Real-time score tracking and leaderboard
- **Responsive Design** - Works on desktop and mobile devices

### Admin Features
- **Admin Dashboard** - Complete user management system
- **CRUD Operations** - Create, read, update, and delete user accounts
- **Leaderboard Management** - View and manage player scores
- **Database Management** - Direct access to user database

## 🛠️ Technologies Used

- **Backend**: PHP 7+
- **Database**: MySQL
- **Frontend**: HTML5, CSS3, JavaScript
- **Authentication**: Session-based login system
- **Hosting**: InfinityFree (SQL211.infinityfree.com)

## 📁 Project Structure

```
project-root/
├── Register.php          # User registration page
├── Login.php            # User login page
├── AdminLogin.php       # Admin authentication
├── index.php           # User dashboard
├── Game.php            # Games selection page
├── G_Letter.php        # Missing letter game
├── profile.php         # User profile page
├── adminD.php          # Admin dashboard
├── logout.php          # Logout handler
└── images/             # Background images directory
```

## 🚀 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/missing-letter-game.git
   cd missing-letter-game
   ```

2. **Database Setup**
   - Import the SQL schema to your MySQL database
   - Update database credentials in all PHP files:
     ```php
     $host = "your_host";
     $db = "your_database";
     $user = "your_username";
     $pass = "your_password";
     ```

3. **Server Configuration**
   - Upload files to your PHP-supported web server
   - Ensure PHP sessions are enabled
   - Verify file permissions for session writing

4. **Admin Access**
   - Create an admin account in the `admins` table:
     ```sql
     INSERT INTO admins (username, password) VALUES ('admin', 'your_password');
     ```

## 🎮 How to Play

1. **Register/Login**: Create an account or login to existing account
2. **Navigate to Games**: Click on "Games" in the navigation menu
3. **Select Missing Letter Game**: Choose the letter guessing game
4. **Play Game**: Guess the missing letter in each word to earn points
5. **Track Progress**: View your scores on the leaderboard and profile

## 👨‍💻 Admin Usage

1. **Admin Login**: Access `/AdminLogin.php`
2. **Dashboard**: Manage users through the admin panel
3. **User Operations**:
   - **Insert**: Add new users to the system
   - **Update**: Modify existing user information
   - **Delete**: Remove users from the database
   - **View Leaderboard**: See all player scores

## 🔒 Security Features

- Session-based authentication
- Password confirmation validation
- SQL injection prevention with parameterized queries
- Input sanitization and validation
- Secure logout functionality

## 🌐 Live Demo

The application is hosted on InfinityFree:
- **Main Site**: [letterguessinggame123.gamer.gd]
- **Admin Panel**: `/AdminLogin.php`

## 📊 Database Schema

Key tables:
- `users` - User accounts and profiles
- `admins` - Administrator accounts
- Columns include: id, name, surname, email, gender, username, password, score

## 🎨 Customization

- **Styling**: Modify CSS in each PHP file's `<style>` section
- **Game Words**: Edit the word array in `G_Letter.php`
- **Scoring System**: Adjust point values in the game logic
- **Rounds**: Change the number of rounds in the game session

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- **Hiren & Deep** - Initial work and development

## 🆘 Support

For support, please email [your-email] or create an issue in the GitHub repository.

---

**Note**: This application was developed as a educational project demonstrating PHP web development skills including user authentication, database management, and game logic implementation.
