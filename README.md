# The Challenge
The challenge is to create a .NET Core web API that will interface with a React front-end, providing it the necessary data. Feel free to use any third party libraries necessary to reach the end result. This exercise is to test the following:
- How you build and structure a .NET Core web API
- Your understanding of RESTful Web Services
- Your understanding of backend to frontend integration
- Ability to take loose requirements and return a finished product

## Requirements
- Create a .NET Core web API with the following functionality:
  - Return a list of all Account Executives from Users.json and include the following properties:
     - Company Name
     - Address
     - Phone
     - Number of Active Tickets (represented by activeTickets)
     - Number of Active Contracts (represented by activeContracts)
  - Return a list of all Companies tied to a specific Account Executive (Companies.json) email address
  - Update an existing Account Executive by email address
  - Add a new Company
  
- Create a React front-end with the following pages:
  - Account Executives
    - List all Account Executives and show all data returned from the API
    - A link to view all Companies associated with a given Account Executive
    - A link to a form to edit an existing Account Executive
  - Companies
    - A form to add a new company

Take as much liberty with the exercise as you would like such that the end result represents something you're proud of.

## Submission
Create a public repo in Github and send us a link to the repo in your GitHub account when you're complete. 

Let us know if you run into any issues or have questions, just send an email to your hiring point of contact any time.