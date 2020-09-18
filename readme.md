npm install express --save
npm install body-parser --save
npm install mysql --save
npm install --save-dev nodemon

run the app
npm run start or npm start


API End Points

    GET /api/v1/employees: will give all employees stored in database
    GET /api/v1/employees/<employee_id>: will give a specific employee with employee_id.
    POST /api/v1/employees : create a employee
    PATCH /api/v1/employees/<employee_id>: update a employee partially
    DELETE /api/v1/employees/<employee_id>: delete a employee
    PUT /api/v1/employees/<employee_id>: update a employee completely