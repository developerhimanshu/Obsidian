## Structure of JWT
- Header
- payload
- Signature

**JWT looks like:**   
==`xxxxx.yyyyy.zzzzz`== 



### Header
The header _typically_ consists of two parts: the type of the token, which is JWT, and the signing algorithm being used, such as HMAC SHA256 or RSA.

`For example:`
```
{ "alg": "HS256", "typ": "JWT" }
```

