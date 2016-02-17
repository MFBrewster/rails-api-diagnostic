# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
A backend allows a program to store data which can be accessed remotely by one
or more people simultaneously, so that the data doesn\'t depend on the machine
from which it\'s being accessed
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
the model
```

Which layer in the MVC pattern communicates with the model?

```bash
the controlled
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
because we don\'t need it, our users\' view will be handled in the browser
```

What does C.R.U.D stand for?

```bash
create, read, update, delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
the model
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
-the controller receives the get request
-the controller tells the model to query the database for person/1
-the model interacts with the database to get the requested data, and passes
 it back to the controller
-the controller sends the requested data back to the user
```

What is the command to generate a new rails-api app?

```bash
rails-api new //app name//
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
- rake db:drop
- rake db:create
- rake db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
rails-api g scaffold pet name:name age:age
```

List two advantages of using serializers? (2 bullet points)

```bash
1. Serializers allow the backend to hide certain types of data (like passwords).
2. They also allow the creation of relationships between data types

```
