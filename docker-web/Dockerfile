FROM microsoft/dotnet:2.1-aspnetcore-runtime-alpine3.7 as base
WORKDIR /app
EXPOSE 8080
COPY ./bin/Debug/netcoreapp2.1/* ./
WORKDIR /app
ENTRYPOINT [ "dotnet", "docker-sample.dll" ]