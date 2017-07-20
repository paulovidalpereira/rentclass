# Register
Creating new users.

### Request
```
POST /register
```

### Headers
```
Accept: application/json
```

### Parameters:
```
name: required, string, max 255
email: required, string, type email, max 255, unique
password: required, string, min 6, confirmed
```

### Response
Status:
```
201
```
Body:
```
{
  "data": {
    "message": "ok"
  }
}
```
