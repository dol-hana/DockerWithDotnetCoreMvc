# DockerWithDotnetCoreMvc

Docker with dotnet core MVC

1. create a folder : c:\users\dol_h\source\test1
2. change directoty to test1 
3. test1> dotnet new mvc
4. docker pull microsoft/aspnetcore-build
5. docker run
	-it
	-p 8080:80
	-v "%cd%":/app
	-w "/app"
	microsoft/aspnetcore-build
	/bin/bash

6.dotnet restore
7.dotnet build
8.dotnet run

9. open a browser : http://localhost: 5000

10. change source code and save it
11. refresh the browser
