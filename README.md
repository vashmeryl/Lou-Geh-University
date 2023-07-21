Lou Geh University Management System is a web-based application which allows you to add, edit, delete information about the students, the courses they take along with the subjects and the grades of the student.

Please read the guide on how to set up the application:

For installation:

1. Download and install xampp
2. Download the LGUniversity files and extract it from the .rar/.zip folder it is in
3. Put the folder in xampp/htdocs/ folder

For Database import:

1. Open xampp and turn on Apache and MySQL
1. Open browser and search localhost/phpmyadmin/
3. Go to Import at the navbar and click Choose File and search the database file in 4. xampp/htdocs/LGUniversity/db_univerity.sql
4. Once you've selected the file, scroll down click the Import button

For Accessing the application:

1. Search in the browser http://localhost/lguniversity/index.html
2. The navigation allows you to choose what you want to do within the application. Be it add/edit/delete a course, check the database, etc.
3. You can navigate the application and add/edit/delete any information you want.

In case sql won't run:

1. Open .sql file using notepad/any other application viable
2. Create new db_university table in Mysql
3. In the db_university table, open the SQL tab
4. Refer to the .sql file opened within the notepad and copy from CREATE TABLE up to DEFAULT CHARSET=utf8mb4;
5. Paste it in the SQL tab
6. Repeat for all tables
