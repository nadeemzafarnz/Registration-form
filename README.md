# Registration-form
Implement functions or methods for each CRUD operation (Create, Read, Update, Delete) using your chosen programming language and framework.
8. Run the Application
Start the Spring Boot application by running the RegistrationApplication class.
Test the APIs using Postman or any REST client.
9. Example API Calls
Create a Registration
POST: http://localhost:8080/api/registrations
Body:

json
Copy code
{
  "name": "John Doe",
  "email": "john.doe@example.com",
  "dateOfBirth": "1990-01-01",
  "phoneNumber": "1234567890"
}
Get All Registrations
GET: http://localhost:8080/api/registrations

Update a Registration
PUT: http://localhost:8080/api/registrations/{id}
Body:

json
Copy code
{
  "name": "Jane Doe",
  "email": "jane.doe@example.com",
  "dateOfBirth": "1991-01-01",
  "phoneNumber": "0987654321"
}
Delete a Registration
DELETE: http://localhost:8080/api/registrations/{id}
