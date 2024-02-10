# Backend Library Server Assignment

## Instructions to Access the Backend Server:
Clone this repository to your local machine.
Install the necessary dependencies using npm install.
Start the server using npm start.
Access the endpoints using a tool like Postman or any HTTP client.
Important Notes:
The backend server uses JWT for authentication. Make sure to include the generated token in the Authorization header for authenticated requests.
Ensure that the CSV files (adminUser.csv and regularUser.csv) are present in the project directory and have the required structure.

## Key Points:
### Authentication and Authorization:

Implemented authentication using JWT.
Differentiate between Admin and Regular users for authorization purposes.

### Endpoints:

Implement /login endpoint for user authentication.
Implement /home endpoint to fetch books based on user type.
Implement /addBook endpoint for adding books (accessible only to Admin).
Implement /deleteBook endpoint for deleting books (accessible only to Admin).


### CSV File Handling:

Read and write book data to CSV files (adminUser.csv and regularUser.csv).
Validate CSV file existence and structure before performing operations.

### Use below information for Login
Regular User Info : {username: 'regular', password: 'regular', userType: 'regular'} &&&
Admin User Info : { username: 'admin', password: 'admin', userType: 'admin' }
