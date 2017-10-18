## NodeJS Project for Hacktoberfest 2017
Create a NodeJS server using ExpressJS and other NPM modules, capable of hosting the official Mozilla Campus Club website with API endpoints for core functions. Data storage & retrieval should be conducted via the JSON files stored in the _/config_ directory. You are free to create as many JSON files with structures as needed, however limit each endpoint type (ex: _/api/v1/members/..._) to a single JSON file (ex: _/config/members.json_).

### Installing Node and NPM
Refer the tutorial [here](https://nodejs.org/en/download/package-manager/) to install Node and NPM in your desired operating system.

### Recommended IDE
The latest version of IntelliJ WebStorm is recommended for this project. You can obtain a student license [here](https://www.jetbrains.com/student/). Install your desired IDE only after installing Node and NPM to avoid configuration issues.

### Getting Started
1. Navigate to a directory on your local machine and execute `git clone <repo>`
2. Enter the cloned directory (/NodeJS) and execute `npm i` to install the relevant NPM modules 

### Endpoints
1. POST - /api/v1/members/register
2. GET - /api/v1/members/:id
3. GET - /api/v1/members/auth (available only for admin members)
3. GET - /api/v1/members/list
4. DELETE - /api/v1/members/:id
5. POST - /api/v1/events/register
6. GET - /api/v1/events/:id
7. GET - /api/v1/events/list
8. DELETE - /api/v1/events/:id

Find instructions for the relevant endpoints in the Issues section of this repo.

### Debugging and Testing
Use [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en) to test the API endpoints.

### Notes
Refer the Projects section to view the development stages of this application.