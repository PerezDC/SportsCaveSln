<p align="center">
<img src="https://github.com/PerezDC/SportsCaveSln/blob/master/Sport-Cave-Logo-1024x1024.jpg" alt="SportsCaveLogo" width="500" height="500">
</p>
# SportsCaveSln
Student demo based on Adam Freeman's book, https://www.apress.com/gp/book/9781484254394

## Create Solution and Projects
    dotnet new globaljson --sdk-version 3.1.302 --output SportsCaveSln/OutdoorProducts
    dotnet new web --no-https --output SportsCaveSln/OutdoorProducts --framework netcoreapp3.1
    dotnet new sln -o SportsCaveSln
    dotnet sln SportsCaveSln add SportsCaveSln/OutdoorProducts 
    dotnet new xunit -o SportsCaveSln/OutdoorProducts.Tests --framework netcoreapp3.1
    dotnet sln SportsCaveSln add SportsCaveSln/OutdoorProducts.Tests 
    dotnet add SportsCaveSln/OutdoorProducts.Tests reference SportsCaveSln/OutdoorProducts

