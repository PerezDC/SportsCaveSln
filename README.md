<p align="center">
    <img src="https://github.com/PerezDC/SportsCaveSln/blob/master/Sport-Cave-Logo-1024x1024.jpg" alt="SportsCaveLogo" width="500" height="500">
</p>

# SportsCaveSln
* Student demo based on Adam Freeman's book, *Pro ASP.NET Core 3*, which can be accessed [here](https://www.apress.com/gp/book/9781484254394).

----
## Chapter 1
### Create Solution and Projects
    dotnet new globaljson --sdk-version 3.1.302 --output SportsCaveSln/OutdoorProducts
    dotnet new web --no-https --output SportsCaveSln/OutdoorProducts --framework netcoreapp3.1
    dotnet new sln -o SportsCaveSln
    dotnet sln SportsCaveSln add SportsCaveSln/OutdoorProducts 
    dotnet new xunit -o SportsCaveSln/OutdoorProducts.Tests --framework netcoreapp3.1
    dotnet sln SportsCaveSln add SportsCaveSln/OutdoorProducts.Tests 
    dotnet add SportsCaveSln/OutdoorProducts.Tests reference SportsCaveSln/OutdoorProducts
    
----

### Configure and Build
![Screenshot1](https://github.com/PerezDC/SportsCaveSln/blob/master/ImageFiles/ScreenShot1.PNG)

----

### Connecting to the Database
![Screenshot2](https://github.com/PerezDC/SportsCaveSln/blob/master/ImageFiles/ScreenShot3.PNG)

----

### Displaying the Products with bootstrap styling
![Screenshot3](https://github.com/PerezDC/SportsCaveSln/blob/master/ImageFiles/ScreenShot2.PNG)

----

## Chapter 2
### Add, Filter, and highlight Category
![Screenshot1Chapter8](https://github.com/PerezDC/SportsCaveSln/blob/master/ImageFiles/Chapter%208/LAB2A%20-%20Screenshot1%20-%20DPerez.PNG)

----

### Add Shopping Cart and Session Data
![Screenshot2Chapter8](https://github.com/PerezDC/SportsCaveSln/blob/master/ImageFiles/Chapter%208/LAB2A%20-%20Screenshot2%20-%20DPerez.PNG)
![Screenshot3Chapter8](https://github.com/PerezDC/SportsCaveSln/blob/master/ImageFiles/Chapter%208/LAB2A%20-%20Screenshot3%20-%20DPerez.PNG)

----

### Current Tests Status
![Screenshot4Chapter8](https://github.com/PerezDC/SportsCaveSln/blob/master/ImageFiles/Chapter%208/LAB2A%20-%20Screenshot4%20-%20DPerez%20Formatted.PNG)

* All tests can be viewed in the [OutdoorProducts.Tests](https://github.com/PerezDC/SportsCaveSln/tree/master/OutdoorProducts.Tests) Project.

----

## Chapter 3
![Screenshot1Chapter3](https://github.com/PerezDC/SportsCaveSln/blob/master/ImageFiles/Checkout%20Screenshot%201.PNG)
![Screenshot2Chapter3](https://github.com/PerezDC/SportsCaveSln/blob/master/ImageFiles/Checkout%20Screenshot%202.PNG)
![Screenshot3Chapter3](https://github.com/PerezDC/SportsCaveSln/blob/master/ImageFiles/Checkout%20Screenshot%203.PNG)
![UpdatedTests](https://github.com/PerezDC/SportsCaveSln/blob/master/ImageFiles/Updated%20Tests%20Screenshot%204.PNG)

----

## Chapter 4
![Screenshot10Chapter4](https://github.com/PerezDC/SportsCaveSln/blob/master/ImageFiles/Chapter10Screenshot.png)
