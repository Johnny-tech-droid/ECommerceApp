# ECommerceApp
This is a simple E-Commerce Web-App built with C#, HTML, CSS, and JavaScript. 
It is a simple web application that allows users to view products. The application is built with ASP.NET Core MVC and Entity Framework Core.

## Database variant

This version uses **SQL Server LocalDB** (`UseSqlServer`, connection string in `appsettings.json`) and
therefore runs on Windows. The cross-platform variant with **SQLite** lives in
[ecommerceCrossPlatform](https://github.com/Johnny-tech-droid/ecommerceCrossPlatform).

## Run

Requires the .NET 8 SDK and SQL Server LocalDB.

```bash
dotnet tool install --global dotnet-ef
dotnet ef database update
dotnet run
```

## License

MIT, see [LICENSE](LICENSE).

## Contact

Johnny-tech-droid · contact@hausrund.info · https://github.com/Johnny-tech-droid
