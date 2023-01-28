# Taxi_service_management
## Affectation of Taxis and Drivers Management System
>Page "Taxis" is a PHP script that displays a form to add a taxi to a database and a table to show the list of taxis in the database. The form includes inputs for ID, number, brand, and model. When the form is submitted, the script connects to a database called "taxi_orga" using the credentials provided and inserts the input values into the "TAXI" table. The script then retrieves all the rows from the "TAXI" table and displays them in a table.
>Page "chauffeurs" is a a PHP script that creates a form to insert, update, or delete a driver in a MySQL database. It also displays a table of all the drivers in the database. The form uses the POST method to send the data to the server and the server then uses the data to update the database. The script starts by setting up a connection to the MySQL database, using the MySQLi library. The script also uses Bootstrap, Jquery and CSS for styling.


>Page "api" is a PHP script that connects to a MySQL database named "taxi_orga" using the connection parameters: $servername, $username, $password, $dbname. It then retrieves all the rows from a table called "TAXI" using the SELECT statement and stores the result in the variable $results. It then iterates through each row of the result set, creating an associative array with the row's data, and appends that array to the $arr variable. Finally, it echoes the JSON encoded version of the $arr variable. The commented out section is similar to the first one, but it creates an object of class "orgtx" for each row and adds it to an array called $taxiarr. And it will json_encode the $taxiarr.


>Page "Reservations" is a PHP script that displays a form for adding, updating, and deleting "affectations" in a database. The form allows the user to select a taxi and a driver from lists of existing taxis and drivers in the database, and enter information about the affectation such as date, KM and incident. The script also includes a button that opens a modal for updating an existing affectation. The form submits data to the same page through the use of the post method when the user press the submit button. The script appears to be using Bootstrap for styling and the mysqli extension for interacting with the database.
