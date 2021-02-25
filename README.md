# oneM2M-IoT-Dashboard


1) Install required node modules for frontend and backend using the following command:
> cd frontend  
> npm install 

> cd backend  
>npm install


2) Configure the backend/config/default.json for your oneM2M CSE
```
        var originator="Cae-admin";//Super user with admin rights
        var cseUri = "http://127.0.0.1:8080";//IP address and port
        var cseName = "server";//CSE Name
```		

3) Start the dashboard
Start the IoT dashboard using the following command:
```
>  cd frontend   
>  node app.js

>  cd backend   
>  npm start

```

4) access the dashboard on port 4100
```
http://localhost:4100
```

