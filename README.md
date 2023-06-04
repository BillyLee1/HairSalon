# VendorOrder

#### Basic webapp to allow you to add stylists and clients.

#### By Billy Lee

## Technologies Used

* _C#_
* _.NET_
* _MVC_
* _mysql_
* _EntityFrameworkCore_
* _Razor Markup_
* _ASPNetCore_
* _linq_


## Description
_This is a simple web app that allows you to create stylists and vendors for a hair salon. You may also add clients and descriptions of the clients. Details about the client and the stylist the client sees is viewable on their details page._

## Setup/Installation Requirements

#### Installing .NET & MySQL
* _First, install .NET 6_
* _If it is not installed, please install .NET 6 with this link (https://dotnet.microsoft.com/en-us/download/dotnet/6.0)_
* _Open the file_
* _Follow the installation intructions_
* _To confirm the the installation, on your command line in your terminal type "dotnet --version"_
* _install MySQL. Follow the instructions in here(https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-and-configuring-mysql)._

#### Cloning the project file
* _Visit the repository this project is located in._
* _Press the green code button and copy and the HTTPS link that ends with .git_
* _Open up your gitbash and change the directory to where you want to clone this repository._
* _in gitbash, type "git clone" and then paste the link you just copied._
* _Open the project folder in VS Code by typing "code ." into gitbash_
* _Navigate into HairSalon folder_

#### Configuring appsettings.json
* _Clone the repository_
* _Navigate to the 'Factory.Solution' directory on your computer_
* _Open it in VSCode or any text editor of your choosing_
* _ Go to the "Factory" Directory_
* _Create a new file called "appsettings.json_
* _In the appsettings.json file you will add the following code below_
* _*{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=billy-lee;uid=[YOUR-USERNAME-HERE];pwd=[YOUR-PASSWORD-HERE];"
  }
}*_

#### Importing The Database
* _Open MySQLWorkBench and click your local instance_
* _Click Administration on the left_
* _Click Data Import/Restore_
* _Click Import from self contained file and import the billy_lee.sql file inside of the project folder._
* _The database should be in the schemas tab_

#### Starting The Development Server
* _Navigate to HairSalon.Solution in gitbash_
* _Change directories to HairSalon_
* _Run dotnet watch run_


## License

_Please let me know if you see any bugs within this project. You can contact me through Discord or email me at codingbillylee@gmail.com_

[Copyright](https://opensource.org/licenses/MIT) (c) _2023_ _Billy Lee_
