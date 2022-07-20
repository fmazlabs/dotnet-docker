FROM mcr.microsoft.com/dotnet/aspnet:6.0
COPY --from=build /app ./
ENTRYPOINT ["dotnet", "aspnetapp.dll"]
