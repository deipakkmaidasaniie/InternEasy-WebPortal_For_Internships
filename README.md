# InternEasy-WebPortal_For_Internships

A web portal for Internships where students can find the desired internships based on their skills and locations and recruiters can post the internships. 

## Requirements
- Node.Js version v12.18.0 or higher. Click [here](https://nodejs.org/en/download/) for installing instructions.
- NPM version 6.14.4 or higher. Click [here](https://docs.npmjs.com/getting-started) for installing instructions.
- Postman for API Testing. Click [here](https://www.postman.com/downloads) for downloading postman.
- Mongo DB for the database. Click [here](https://www.mongodb.com/try/download/community) for downloading.

---
## Installation

## Building the source code

## Generate modules for project
- Build all the modules from package.json. npm is the build system.

    - Install & update the dependencies
    ```sh
    npm install --save
    ```
    - Install & update the dev dependencies
    ```sh
    npm install --save-dev
    ```
## Get it done and running
```sh
npm start
```

## Features:

Recruiter:
- Can Add Internship along with all the necessary details like about the internship, skills required, stipend , location and so on.
- Can View all the applicants
- Can Accept or reject the applicant. If he accept, the mail will be sent to the applicant on his registered mail id and status will be updated to selected in the database.
- Can delete or update the internship
- Can edit his profile


Student:
- Can Apply for the internships based on his preference( skills, location, duration, stipend)
- Can view the status of all the internships he applied to
- Can edit his profile
- If he is selected for any internship, he will be notified through email and web notification.

## Upcoming features:
- Chat system for recruiters to communicate with applicants
- Support for job posting as well




