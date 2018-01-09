# idap-jwt-auth
IDAP JWT Auth0 Authentication

## AngularJS - JWT - Auth0 Example
## -------------------------------
(Also refer to https://github.com/gudiseva/idap-auth-server.git)

1. Sign Up for Auth0:
	a. URL: https://auth0.com/signup
	b. Enter Email / Password
	
2. Create Client for Auth0:
	a. Quick Start -> AngularJS
	b. Copy Callback URL -> http://localhost:3000/callback
	c. Settings -> Allowed Callback URLs -> Paste and Save Changes
	
3. Create directory:
	C:\> D:\WORKSPACE\nodejs_projects\idap-jwt-auth
	
4. Open Command Prompt:
	C:\> npm init (Accept Defaults)
	C:\> npm i --save angular @uirouter/angularjs auth0-js angular-auth0 bootstrap
	
5. Open the project in Visual Studio Code
	C:\> code .

6. Add index.html

7. Add Http Server
	C:\> npm i -g http-server (Note: g is for Global)
	
8. Run the Application	
	C:\> http-server -p 3000 -o

9. Install Express Server
	C:\> npm i --save express
	
10. Run the Server
	C:\> node server.js

11. Create APIs in Auth0 website (New API):
	a. Name -> Nginx API
	b. Identifier -> https://kodiak-demo.com/api
	c. Signing Algorithm -> RS256

12. Make Directory:
	C:\> D:\WORKSPACE\nodejs_projects\idap-auth-server
	
13. Open Command Prompt:
	C:\> npm init (Accept Defaults)
	C:\> npm i --save express express-jwt jwks-rsa cors	(Install dependencies)
	C:\> touch server.js
	
14. Open the project in Visual Studio Code
	C:\> code .
	Copy code snippet from Quick Start to server.js file
	
15. Run the Server
	C:\> node server.js	
	
16. Change directory:
	C:\> D:\WORKSPACE\nodejs_projects\idap-jwt-auth
	
17. Open Command Prompt:
	C:\> npm i --save angular-jwt
	
	
IIFE: Immediately Invoked Function Expression

---