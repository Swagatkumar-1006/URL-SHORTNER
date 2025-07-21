![image](https://github.com/user-attachments/assets/1540583d-ddd0-4067-ab7b-59688d9acac4)


to run frontend :-

PS D:\URL-Shortener\server> node server.js
MongoDB URI: mongodb+srv://healthHack:<password>@healthhack.5noaz.mongodb.net/healthDB
Server running on 5000
Database connection successfull


to run backend :-

PS D:\URL-Shortener> npm run dev
Compiled successfully!

You can now view client in the browser.

  http://localhost:3000

Note that the development build is not optimized.
To create a production build, use npm run build.

webpack compiled successfully

file structure :-

![image](https://github.com/user-attachments/assets/6f2cbcb6-6838-46cc-9503-bd05eebd953e)

.env (client) :-

REACT_APP_API_URL=http://localhost:5000

.env (server) :-

DATABASE_URL = mongodb+srv://healthHack:<YOUR'S MAN>@healthhack.5noaz.mongodb.net/healthDB
PORT = 5000

