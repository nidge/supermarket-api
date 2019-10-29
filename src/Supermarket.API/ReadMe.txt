This tutorial can be found at https://www.freecodecamp.org/news/an-awesome-guide-on-how-to-build-restful-apis-with-asp-net-core-87b818123e28/

The original Github repo can be found here https://github.com/evgomes/supermarket-api

How to Test
First, install .NET Core 2.2. Then, open the terminal or command prompt at the API root path (/src/Supermarket.API/) and run the following commands, in sequence:

dotnet restore
dotnet run
Navigate to https://localhost:5001/api/categories to check if the API is working. If you see a HTTPS security error, just add an exception to see the results.

Navigate to https://localhost:5001/swagger to check the API documentation...