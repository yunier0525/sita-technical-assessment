# SITA Technical Assessment

## Full Stack Developer Assessment - Full
### BackEnd
Our client needs to create and read comments for each flight they have in our system, with the following information:
- ID
- Comment
- Date
- UserId
- FlightId
- Tags

Due to that, we need you to create 2 endpoints using Node Js:

1. Create comment
   
You will receive the following information:
- Comment: String (mandatory)
- UserId: Number (mandatory)
- FlightId: Number (mandatory)
- Tags: String Array (optional)

You have to save the information in the database that you want (Mysql or Mongo) creating a unique ID.

2. Retrieve comments
   
Create an endpoint to retrieve the list of comments for a specific flight ID. You will receive the FlightID and it should return a JSON with the comments.

_Nice to have_
- Express framework
- HTTP Verbs
- Data Validations
- Manage duplicates
- Postman Collection
- Extra functionalities (Sort, Filter …)
- Database: Mongo or Mysql
- Develop using SOLID
- Unit Test
- Documentation

### Frontend

To create and show the comments, our client needs a web page (SPA) developed in Angular 12 + with the following’s components:

- Sidebar to show the list of flights: When the user clicks in a flight, the information in the table should change (The list of flights can be hardcoded in the code or in the database).
- Table to show:
  - Comment ID
  - Comment
  - User
  - Tags
- Button and form to create a new comment.

_Nice to have_
- Use of SASS
- UI/UX Design
- Angular Material
- Data Validations
- Unit Tests
- Documentation
- Pagination – Sort – Filters – Search box
- Responsive Design
- SOLID principle

### Javascript
Given an array of URLs and a MAX_CONCURRENCY integer, implement a function that will asynchronously fetch each URL, not requesting more than MAX_CONCURRENCY URLs at the same time. The URLs should be fetched as soon as possible. The function should return an array of responses for each URL. How would you write a test for such a function?

