# Jobly

Jobly is a mock app where users can view job postings and apply for open positions. The frontend was built with React and the backend was built with Node, Express, and PostgreSQL.

To see a live demo: https://jobilly.herokuapp.com/
* Username: test
* Password: password

![alt text](https://github.com/SKaplan01/react_jobly/blob/master/images/jobly.gif "Jobly Gif")

**To run this repository locally:**

1. git clone
2. `createdb jobly`
3. `psql jobly < data.sql`

*Start the backend server:*
1. cd "backend"
2. `npm install`
3. `nodemon`

*Run the frontend:*
1. cd "frontend"
2. `npm install`
3. `npm start`

**Here's a sample of the JSON returned from the backend (a GET to '/jobs'):**
 
![alt text](https://github.com/SKaplan01/react_jobly/blob/master/images/backend.png "Sample JSON returned from GET to '/jobs'")


Collaborators: https://github.com/hasierpastor/react_jobly


