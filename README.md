# Employee-API
An API that connects to the employee database

URL: http://127.0.0.1:5000/
Endpoint: /employee_information/<int:emp_id>
The endpoint has a mandatory value which is the employee id

The API is built using flask Restful. 
Following are the requests that it can accept:
GET - Get employee information for a specific employee
POST - Create a new employee
PUT - Edit information for an existing employee
DELETE - Delete an employee from the database

Database is created using SQLAlchemy.

Payloads are sent in a JSON format
Mandatory parameters that must be sent are:
First Name
Last Name
Contact Number

Sample Payload = {
                    'first_name' : 'John',
                    'last_name' : 'Doe',
                    'contact_number' : '1234567'
                 }

