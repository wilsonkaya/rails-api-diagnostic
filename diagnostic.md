# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
Backend is where we create a controlling mechanish to create, store and update data with consistency.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
Model
```

Which layer in the MVC pattern communicates with the model?

```md
Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
Because we are rendering it to JSON
```

What does C.R.U.D stand for?

```md
Create Read Update and Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
Controller
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
Index, Create, Show, Update, Delete
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
-When aplications recevies the request the routes will be seperating the url from verb and passing to Controller.
-controller receives the verb "GET" and the url "people/#{ID}" it will be looking for the Modal's for the the structure of the data that we are requesting from databse
- Modals will be getting the data to find the table with Person but looking for a single data with the id of 1.
- Retrived data will be passed to contoller and controller and conroller will be rendering it to Json and turning backto user via browsers.
```

What is the command to generate a new rails-api app?

```bash
rails new fatih_api --api
```

What is the command to start an instance of a rails server?

```bash
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
bin/rake db:drop db:create db:migrate db:seed
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
I dont remember 
```
