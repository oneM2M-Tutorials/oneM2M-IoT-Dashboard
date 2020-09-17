# IoT-Dashboard


1) Install required node modules
Install the required node modules using the following command:
> npm install


2) Configure the index.html to allow the dashboard to access the CSE
```
        var originator="Cae-admin";
        var cseUri = "http://127.0.0.1:8080";
        var cseName = "server";
```		

3) Start the dashboard
Start the IoT dashboard using the following command:
```
>  node app.js
```

4) access the dashboard on port 4100
```
http://ipaddress:4100
```


