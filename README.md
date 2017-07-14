# library
library management system project files

In the src folder of the Application, all the source codes needed for execution of the system are present.
Firstly, the server machine must execute the file initial_query.sql for creation of tables and initialization. 

This project is based on client server architecture. The whole source code is divided into three packages, namely login, admin and librarian packages. Login package contains all the client and server files related to the admin and librarian login. Admin package consists of all the client and server files related to the roles of admin that include registration/removal of a librarian etc., Librarian package consists of all the client and server files related to the responsibilities of a librarian that include registration of a student, adding or issuing books and returning books.

The server machine should run all of the server files available. The client machine need only run one file from the login package which is login_options.java. All other files can be directed to from this file only. 
