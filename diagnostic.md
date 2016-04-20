# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
The backend interacts with a server to return user ready results. The user interacts with the frontend and sends request to the backend to retrieve the requested information.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The model
```

Which layer in the MVC pattern communicates with the model?

```bash
The controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
We are working with single page applications and views are not necessary and slow down processing speed
```

What does C.R.U.D stand for?

```bash
Create Read Update Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
The MVC is a way to divide out the crud actions

```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
index, create, show, update, destroy
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
1) A database must be created
2) A route for the request (eg, /person/:id)
3) A controller must be active
4) A controller method on what action to perform (thing we are technically not supposed to do)
```

What is the command to generate a new rails-api app?

```bash
$ rails new <app>
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
- db: drop
- db: create
- db: migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
g scaffold pet name:string age:string
```

List two advantages of using serializers? (2 bullet points)

```bash
- useful for persistent objects
- api is safer and easier
```
