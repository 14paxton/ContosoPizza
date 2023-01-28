- https://learn.microsoft.com/en-us/training/modules/build-web-api-aspnet-core/6-exercise-add-controller
- https://dotnet.microsoft.com/en-us/apps/aspnet
- https://www.c-sharpcorner.com/article/microservice-using-asp-net-core/
- https://www.c-sharpcorner.com/article/microservice-using-asp-net-core/
-


# HttpRepl

```bash
 dotnet tool install;

export PATH="$PATH:/Users/bp/.dotnet/tools";
httprepl http://localhost:5001                  
```

- list and select controllers
 > ls , cd

- post
```bash
post -c "{"name":"Hawaii", "isGlutenFree":false}"
```