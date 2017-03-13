# google-login
Google Login demonstration based on node.js and Docker

# Installation
Update file ```data/www/index.html```
replace the string
<meta name="google-signin-client_id" content="GOOGLE_CLIENT_ID">
with your google client id. You can register a new client application via google by the following url https://console.developers.google.com/apis/credentials

See Google Tutorial on integrating Google Login in Web Applications for further details:
https://developers.google.com/identity/sign-in/web/devconsole-project

Build your own image or run a new container via 

```docker-compose up```
