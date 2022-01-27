FROM mcr.microsoft.com/dotnet/core/sdk:3.1
WORKDIR /app
COPY . .
ENV ASPNCORE_URLS http://*:5003
EXPOSE 5003
ENTRYPOINT ["dotnet", "demo-github.dll"]
