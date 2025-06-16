 Daily Expense Tracker System
The Daily Expense Tracker System (DETS) is a web-based application that helps users efficiently manage and track their day-to-day expenses. The system allows users to register, log in, and record their expenditures by category and date, making it easier to analyze and manage their financial habits.

Features
- User registration and login system
- Add, view, and manage daily expenses
- Expense tracking by category and date
- Dashboard with total expense overview
- Simple and user-friendly interface
 Technologies Used
- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: PHP
- **Database**: MySQL
- **Server**: Apache (XAMPP/WAMP/LAMP stack)

Installation Steps
1. **Download** the project ZIP file and extract it.
2. Copy the `dets` folder.
3. Paste it into the root directory:
   - For XAMPP: `xampp/htdocs`
   - For WAMP: `wamp/www`
   - For LAMP: `var/www/html`
4. Open your browser and navigate to **PHPMyAdmin**:  
   `http://localhost/phpmyadmin`
5. Create a new database named:  
   `detsdb`
6. Import the SQL file located in the `sql file` folder inside the extracted package (`detsdb.sql`).
7. Run the project in your browser:  
   `http://localhost/dets`
Default User Login
You can either register yourself or use the following test credentials:
- **Username**: `testuser@gmail.com`  
- **Password**: `Test @123`
 Notes
- Make sure your local server (Apache & MySQL) is running.
- This project is for educational/demo purposes and should be secured before deploying in production.
License
This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).
