# Dr. Sillystringz's Factory
### An independent project using many-to-many relationships/ Epicodus Project

### By Theron Packus

## Technologies Used

* Git
* C#
* .NET 5.0
* ASP.NET Core MVC
* Entity Framework Core
* MVC
* RESTful Routing, CRUD & HTTP
* REPL
* MySQL 
* Bootstrap
* HTML

## Description

This C# MVC web application was built to help Dr. Sillystringz manage what engineers are licensed to work what specific machinery. The application will allow him to add engineers and the machines they are licensed to use, to a database. Then view the what machines each engineer in certified to use and vice versa on separate detailed web pages.

## Setup/Installation Requirements

* _Requires Visual Studio Code Installation_
* _Requires Terminal Installation_
* _Open the terminal on your local machine_
* _Navigate to the directory inside of which you wish to house this project_
* _Clone this project with the following command  `$ git clone https://github.com/tlpackus/Factory.Solutions.git`_
* _Next you will need to download and install .NET Core through this link if you don't already have it: https://dotnet.microsoft.com/download_
* _After downloading and installing .NET Core, return to your terminal and navigate to the root directory by entering `$ cd Factory.Solution`_
* _Open this project in Visual Studio Code with the command `$ code .`_
* _Still in the terminal, navigate to the desired subdirectory of the repository with the command `$ cd Factory`_
* _Retrieve and install packages listed in the .csproj files with the command `$ dotnet restore`_
* _Create internal content for build with the command `$ dotnet build`_

**Instructions for re-creating the MySQL Database through a migration**
* _Open MySQL Workbench (If you don't already have it, it can be downloaded here: https://dev.mysql.com/downloads/file/?id=484391)_
* _From the `Factory` directory run command `$ touch appsettings.json` to create a new file._
* _Input the following script_ (**note the name of the database below needs to match the name of the database you created (e.g. test_database)**)
![Image of appsettings.json example](./Factory/wwwroot/img/appsettings.json_example2.png)
* _Back in the terminal run command `$ dotnet ef migrations add Initial`_
* _Next run `$ dotnet ef database update`_
* _Your MySQL Workbench should now show a new Schema added_
* _You can now run $ dotnet run from the Factory Directory to launch, view and use the app in the google browser_


## Known Bugs

- No known bugs so please lets me know if you encounter any through the email I provided below.

## License

[MIT](LICENSE.txt)

Copyright © 2021 Theron Packus

All Rights Reserved

## Support and Contact Information

For contact support or any found bugs, please email me here <a href = "mailto: tlpackus@gamil.com">Send Email</a>