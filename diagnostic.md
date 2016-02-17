# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
The purpose of the backend is to partially conduct Create Read Update Modify Destroy data along with conducting backend logic.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The Model.
```

Which layer in the MVC pattern communicates with the model?

```bash
Controller communicates to the model.
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
the current standard is to use single pages sites insted of multi-page sites.
```

What does C.R.U.D stand for?

```bash
Create. Read. Update. Destroy.
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
In the controller.
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
INCOMMING:
Browers send GET /person/1 to web server
webserver then passes it to Routes
if route exists then passes requestto controller
if it exists controller sends person#show
model conducts person#show on Database

OUTGOING:
Database sends person 1 to model
model passes data to controller
controller speaks to server
server sends to browser.
```

What is the command to generate a new rails-api app?

```bash
rails-api new thing_app -T --database=postgresql
```

What is the command to start an instance of a rails server?

```bash
rails s
OR
rails server
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
Drop database mydb
crate database mydb
migrate cats, mydb
```

What is the command to scaffold a pet with a name and an age?

```bash
rails-api g scaffold pet name:string age:integer
```

List two advantages of using serializers? (2 bullet points)

```bash
Makes our api a little bit safer and easier to use.
```
