Database Setup (Required for Login)

To use the login feature of this project, you must connect the database first. Without database connection, authentication will not work.

⚙️ Steps to Setup Database
1.Install Database Software
Install MySQL
Create Database
Open your database tool (MySQL Workbench)

Create a new database:
Database Name: farmiti   (or your project name)
Import the .sql file (for MySQL)
Configure Backend Connection

Go to backend folder:

2. /farmiti-backend/config/db.js   (or .env file)

Update database credentials:

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=farmiti
3.next go to the terminal
Start Backend Server 
cd farmiti-backend
npm install
npm run seed
npm run dev

4.Run Frontend

cd farmiti-frontend
npm install
npm run dev
⚠️ Important Note
Login/Signup will NOT work if the database is not connected.
Make sure the database server is running before starting the backend.

✅ mandatory(DB_password)

You can also add a .env.example file to help others:

DB_HOST=
DB_USER=
DB_PASSWORD=
DB_NAME=
