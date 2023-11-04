# oauthsever
A simple Oauth Server

## go run main.go
## curl http://locahost:9096/protected 
* This will return you error
## curl http://localhost:9096/credentials
* This will return you CLIENT_ID and CLIENT_SECRET
## start and browser client, and paste the following request,
http://localhost:9096/token?grant_type=client_credentials&client_id=<CLIENT_ID>&client_secret=<CLIENT_SECRET>&scope=all

Note: replace the CLIENT_ID & CLIENT_SECRET to the ones generated in earlier step.
