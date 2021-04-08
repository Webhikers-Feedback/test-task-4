# test-task-3

## Tasks

### 1. Write a `Node.js` server using `Express` and `Mongoose` to connect with `MongoDB`.

### 2. Setup 3 Database Models (`Posts`, `Clients`, `Orders`)

2.1 One `Order` must have a relation to client, the `Client` must not have a relation to the `Order`.
2.2 You can choose some fields of your own choice for the models.

### 3. Write an API for all 3 models, to create, update, delete and get them.

3.1 When an `Order` is created you need to check if a `Client` for this `Order` already exists. If yes, you need to attach it, if not you need to create it first and then attach it.

3.2 When you want to `GET` an `Order` you also need to send the client data in the api response.

3.3 Write the api as modular as if you would do it, if this was going to be a large scale application. The quality of modular thinking will be crucial to our hiring decisions.

### 4. Write and use a global function for api response

Write a global and reusable for all api responses, so the response object structure and error handling can always be controlled from one place only.

### 5. The API must be fully working.
