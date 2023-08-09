<h1 align="center" id="title">User Management Profile</h1>

<p id="description">The User Management API Project is a backend solution designed to provide essential functionalities for user registration authentication and user profile management. As a backend engineer My task is to design and implement this API ensuring secure and seamless user interactions. This is an assessment i completed through FAST CREDIT NG.</p>

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   User Registration
*   User Authentication
*   User Profile Retrieval
*   Update
*   Assumptions
*   Running the API
*   Testing

<h2>User Registration</h2>
Endpoint: POST /api/register

Registers a new user.

INPUT



OUTPUT

<h2>User Authentication</h2>
Endpoint: POST /api/authenticate

Authenticates a user.

INPUT

OUTPUT

<h2>User Profile Retrieval</h2>
Endpoint: GET /api/profile

Retrieves the user's profile information.

INPUT

OUTPUT

<h2>User Profile Update</h2>
Endpoint: PUT /api/profile

Updates the user's profile information.

INPUT

OUTPUT

<h2>Assumptions</h2>
<p>Passwords are securely hashed using industry-standard cryptographic algorithms before storing them in the database.
The database schema includes tables for user details and authentication tokens.
Token-based authentication is used, and the token is passed in the Authorization header.</p>
<h2>Running the API</h2>

* Clone this repository.
* Set up your database connection in the appsettings.json file.
* Run migrations to create the database schema: dotnet ef database update
* Build and run the API: dotnet run

<h2>Testing</h2>
Unit tests and integration tests are included in the Tests folder. You can Run tests using the command: dotnet test.



