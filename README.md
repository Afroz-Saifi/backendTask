# backendTask

schema:
    {
        "id": id, 
        "user_name": string, 
        "age": integer,
        "email": email (unique)
    }

GET /users 
    response: all users list
    
POST /users
    add new user
    response: new user object

GET /users/:id
    reponse: user by id

PUT /users/:id
    update user by id
    response: updated user data 

DELETE /users/:id
    delte user by id
    response: deleted user data

GET /users/adults
    response: all user above age 18 (including 18   )


