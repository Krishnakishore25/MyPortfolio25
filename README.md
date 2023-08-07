I have already developed the front end side of my Portfolio website.Here I have done the database connection.I used PHP Language to perform database connection.Basically my Portfolio website shows about myself, my educational qualifications and professional experiences.

My services, the projects I have developed also included in my portfolio. The viewers who view my Portfolio can contact me any time.For that, I have included a Contact form. There is a contact option in my portfolio. When the viewer send their details and their inquiries and press the submit button, the details will be saved in my database. I connected that form with database using PHP.

Contact form is designed to handle a contact form submission and store the form data in a MYSQL database.The process happens when presses the submit button.
1.Includes the "dbconnection.php" file to establish a database connection.
2.Connects to a MYSQL database using the provided server credentials.
3.Retrieves form data(Name, Email, Message) submitted through an HTTP POST request.
4.Constructs an SQL query to insert the form data into a table named "contactform" in the database.
5.Executes the SQL query and displays a success message if the insertion is successful.
6.If an error occurs during the database operation, it displays an error message along with the error details.
7.Closes the database connection.
8.This PHP file serves as the backend logic for handling incoming contact form submissions and storing them in a database for later retrieval and processing.

I have included a Register option for viewers who needs to develop a website/Application.They have to create an account first.After that they can view the package details and other clarifications.

The process in signup(Register) form:
1.Includes the "dbconnection.php" file to establish a database connection.
2.Retrieves form data (Username, First Name, Middle Name, Last Name, Mobile Number, Password, Confirm Password) submitted through an HTTP POST request.
3.Validates that none of the required fields are empty.
4.Connects to a MySQL database using the provided server credentials.
5.Checks if a user with the same Username already exists in the "signup" table.
6.If the Username is not found, prepares an SQL query to insert the user's information into the "signup" table.
7.Executes the SQL query and displays a success message if the insertion is successful.
8.If a user with the same Username already exists, displays an error message.
9.Closes the database connection.
10.This PHP file provides the functionality to allow users to sign up, and their information will be stored in the database for future reference.

Login form:
This PHP file functions as a backend script for user authentication, specifically for a login system. It enables users to log in and verifies their credentials against those stored in a MySQL database. The file performs the following steps:

1. Includes the "dbconnection.php" file to establish a database connection.
2. Retrieves form data (Username, Password) submitted through an HTTP POST request.
3. Connects to the MySQL database using provided server credentials.
4. Prepares an SQL query to retrieve user data from the "signup" table based on the provided Username.
5. Executes the SQL query and fetches the result.
6. Checks if a user with the provided Username exists in the database.
7. If the user exists, compares the stored password with the provided Password.
8. If the passwords match, it displays a "Login Successful" message; otherwise, it shows an "Invalid Email or password" message.
9. If the user doesn't exist, it also displays an "Invalid Email or password" message.

These PHP file serves as the backend logic for user login functionality, validating user credentials and providing appropriate feedback. Be sure to update the server credentials and database details before using it.
