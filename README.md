# Link-Shortener
Simple project made in 3 hours to shorten links. Tech used: Express,EJS

# Versions:
- 1.0.0 initial release
- 1.1.0 API update

# 1.1.0:
- Added: CRD operations (Create Read Delete)
- Added: Register/Login/Read/Create/DELETE API's
- Added: login/register page
- Added: user page

# how to use it?
- clone the repo
- run command "npm i" to install the modules
- run command "npm start" to start in node
- run command "npm run dev" to start in nodemon

# how does it works?
it uses API's and Server routers with Express, EJS for templating
- you can create new shorten link with /api/query?linkName=New&link=https://example.com
- or you can use it to redirect with /shorten/New