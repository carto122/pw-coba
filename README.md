# pw-coba

# RESPUL API Users

# Registrasi Users

## Request body :
```json
{
  "email":"example@gmail.com",
  "password":"rahasia",
  "username": "carto"
}
```
## Response success :
```json
{
  "message": "success",
  "code": 200,
  "data": {
    "email":"example@gmail.com",
    "username": "carto"
  }
}
```
## Response Failed :
```json
{
  "message": "error",
  "code": 401,
  "data": {
    "username or password or email is wrong"
  }
}
```
