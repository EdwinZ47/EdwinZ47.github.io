```{
  method: 'post',
  url: 'https://my-movie-list-2.herokuapp.com/login',
  withCredentials: true,
  data: {
      user: user,
      password: pw
  }
}```
 

Purpose: Login to the server.

Endpoint: POST - https://my-movie-list-2.herokuapp.com/

Params:
    User (string): Required, username of the person logging in
    Password (string): Required, corresponding password of username.

Response: Returns either with a response of true for successful logins, a 404 error for non-existing users, or a 403 error for incorrect password.

