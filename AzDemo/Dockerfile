FROM microsoft/dotnet:2.2-aspnetcore-runtime AS runtime
WORKDIR /app
COPY / /app/
EXPOSE 12300-22300
ENTRYPOINT ["dotnet", "Azdemo.dll"]