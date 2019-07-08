# php-jwt-auth
Jwt based authentication system in PHP

Run the server `php -S localhost:8080`

Use Postman to register a user

`http://localhost:8080/api/register.php`

Pass the necessary fields.

```
{
  "name": "user_name",
  "email": "example@example.com",
  "password":"password"
}
```
<br><br>
To login 

`http://localhost:8080/api/login.php`

```
{
  "email": "example@example.com",
  "password":"password"
}
```

`Note:` Import the `jwt.sql`
