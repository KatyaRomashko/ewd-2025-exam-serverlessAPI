# Enterprise Web Development Exam Starter.

## Instructions to the student.
This repository contains the starting code for a lab-based exam on the Enterprise Web Development module.

### Setup

You are required to take the following steps in preparation for this exam: 

+ Create a copy of it in your own GitHub account.
+ Import the copy into VS Code and run the following commands:
~~~
$ npm install
$ npm run schema
$ git add -A
$ git commit -m "Added dependencies."
$ git push origin main
~~~

### The App.

The app's infrastructure includes some constructs for a serverless REST API. Its Dynamo table stores information about cinema movie schedules. Examine the seed data in `seed/movies.ts` to fully understand its structure. [NOTE: This current table declaration in the stack file is incomplete and will cause a deployment to fail. The correct code will be provided in the exam question.]