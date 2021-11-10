# Authorization/Authentication


### What header(s) are used in authentication and authorization
* The WWW-Authenticate and Proxy-Authenticate response headers define the authentication method that should be used to gain access to a resource. They must specify which authentication scheme is used, so that the client that wishes to authorize knows how to provide the credentials.

### What is safe to put into a JWT
* add "secret" that is used to generate the JWT. If someone modifies the data contained in the JWT, the server will fail to decode it. So the server can trust any JWT that it can decode.

### How are JWTs validate
* the server validates the username and password combination and creates a JWT token with a payload containing the user technical identifier and an expiration timestamp.

---

### RBAC
* Role-based access control (RBAC) is a policy-neutral access-control mechanism defined around roles and privileges.

### User Roles
* are permission sets that control access to areas and features within the Professional Archive Platform.

### JWT Token
* SON Web Token (JWT) is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object

#### Which 3 things had you heard about previously and now have better clarity on?
1. authentication & authorization
2. User Roles

#### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
1.  JWT
2.  Bearer Authorization
3.  Cookies

