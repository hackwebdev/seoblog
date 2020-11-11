create .env

```
NODE_ENV=
PORT=
CLIENT_URL=
DATABASE_LOCAL='mongodb://localhost:27017/databasehere'
JWT_SECRET=

To signin
POST http://localhost:8000/api/signin
{
	"email": "sha@gmail.com",
	"password": "iloveyou"
}
copy the token value

From the Headers

key - Authorization

value - Bearer + token

When signin
GET http://localhost:8000/api/secret
- gets access to the secret page

To signout
GET http://localhost:8000/api/signout
- gets a reply Signout success
```

1:51:14
