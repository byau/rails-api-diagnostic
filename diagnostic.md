# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
// your response here
backend pretty much is all the behind the scene stuff.  To name a few: it can store data, access url, control (logic) how/what the users can interact with the web and the servers, allow information to be shared across accounts and user.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
// model
```

Which layer in the MVC pattern communicates with the model?

```bash
// controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
// the view is used to render the user interface.  we are using a single page where information can be selectively upated.  so it is not necessary to have that everytime
```

What does C.R.U.D stand for?

```bash
// your response here
CREATE
READ
UPDATES
DESTROY
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
// Controller.  Since these are requests, the controller handle them and decide the course of actions (such as talk to model or returns errors, etc).
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
// your response here
the GET request for `person/1` will be sent and 'activate' the 'person' controller.  the controller will recongizned that it is looking for the information of person id# 1 under the person datebase.  If the person model exist, it will send the request to 'person' model to retreive such information.  The model will then relay the information back the to controller. Then the controller will return the information back. If such model/database dont exist, controller will return an error.
```

What is the command to generate a new rails-api app?

```bash
// your response here
rails-api <folder name> ... (as ... for other options)
i.e.: rails-api new blog_app --skip-javascript --skip-sprockets --skip-turbolinks --skip-test-unit --database=postgresql
will start "new blog app" as a rail and with database in postgresql
```

What is the command to start an instance of a rails server?

```bash
// your response here
rails server
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
// your response here
rake db:drop
rake db:create
rake db:migrate

```

What is the command to scaffold a pet with a name and an age?

```bash
// your response here
rails-api g scaffold pet name:string age:integer
```

List two advantages of using serializers? (2 bullet points)

```bash
// your response here

```
