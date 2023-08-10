<h1 align="center" id="title">User Management Profile</h1>

<p id="description">The User Management API Project is a backend solution designed to provide essential functionalities for user registration authentication and user profile management. As a backend engineer My task is to design and implement this API ensuring secure and seamless user interactions. This is an assessment i completed through FAST CREDIT NG.</p>

<h2>Screenshoot of the API ENDPOINTS</h2>  

![image](https://github.com/dejidee0/User-Management-Profile/assets/107705210/ebe0055a-2aff-411e-8456-5df84c9fe626)


  
<h2> Features</h2>

Here're some of the project's best features:

*   User Registration
*   User Authentication
*   User Profile Retrieval
*   Update
*   Assumptions
*   Running the API
*   Testing

<h2>User Registration</h2>
Endpoint: POST /api/UserProfile/Create/User

Creating a new user.

INPUT
![image](https://github.com/dejidee0/User-Management-Profile/assets/107705210/15d7218f-469a-43da-bfa6-1020e260e3e6)



OUTPUT
![image](https://github.com/dejidee0/User-Management-Profile/assets/107705210/65f05f88-42a6-4d44-9dc8-144ae49b2a27)


<h2>User Authentication</h2>
Endpoint: POST /api/UserProfile/authenticate/User

Authenticating a user.

INPUT
![image](https://github.com/dejidee0/User-Management-Profile/assets/107705210/49eb7f9e-d0d0-4a5f-b92a-647fa2cc9a2b)

OUTPUT
![image](https://github.com/dejidee0/User-Management-Profile/assets/107705210/a4aeab55-28a4-4fa3-b4bf-bc72c0bb54b7)

<h2>Get User Profile</h2>
Endpoint: GET /api/Userprofile/User/Profile

Retrieves the user's profile information.

INPUT
![image](https://github.com/dejidee0/User-Management-Profile/assets/107705210/d81e910a-6f84-4f24-96ed-ff2e7fc9878f)

OUTPUT
![image](https://github.com/dejidee0/User-Management-Profile/assets/107705210/824dfd6d-7fd8-45a0-bdae-b13aa3b09b01)

<h2>User Profile Update</h2>
Endpoint: PUT /api/Userprofile/Update/User/Profile

Updates the user's profile information.

INPUT
![image](https://github.com/dejidee0/User-Management-Profile/assets/107705210/73dcf7e7-d735-495f-a81a-2baa2565cf4a)

OUTPUT
![image](https://github.com/dejidee0/User-Management-Profile/assets/107705210/ffc87e88-1b0c-4348-93a9-e07aeef6082f)

<h2>Assumptions</h2>
<p>Passwords are securely hashed using industry standards
The database schema includes tables for user details and authentication tokens.
Token-based authentication is used and it can only be valid for the user under one hour before expiry, and the token is passed in the Authorization header.</p>
<h2>Running the API</h2>

* Clone this repository.
* Set up your database connection in the appsettings.json file.
* Update-Database through migrations to create the database schema: dotnet ef database update
* Build and run the API: dotnet run

<h2>Testing</h2>
Unit tests is included in the Tests folder. You can Run tests using the command: dotnet test.

![image](https://github.com/dejidee0/User-Management-Profile/assets/107705210/6f90962e-0dd1-450e-8a70-90bb804cd8b7)



