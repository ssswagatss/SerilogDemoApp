# RUN the dotnet core web app.
Then run the following docker command to start the **SEQ** server
 ```bash
docker run --name seq -e ACCEPT_EULA=Y -p 8082:80 datalust/seq:latest
```
