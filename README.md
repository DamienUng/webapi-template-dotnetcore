# webapi-template-dotnetcore
Dotnet core web api template with:

1. Unit tests, 
2. Serilog, and 
3. Docker set up.

To see it run locally, at the root of the project: 
```bash
dotnet restore
dotnet run
```

To see in run in docker, in src/:
```bash
docker build -t webapi-template .
docker run -p 5000:5000 --net=host webapi-template
```
