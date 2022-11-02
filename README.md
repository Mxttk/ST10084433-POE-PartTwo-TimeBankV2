Welcome to the README for Time Bank!

This app has been designed with ease of use in mind, consider your time saved already!
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
**NB**
Changelog:

- Data persistence has been added (Note additional software requirements below)
- Ability to register and login with a username and password has been added

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Author: Matthew Kidwell
Version: 2.0

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Software requirements:

- Microsoft Visual Studio 2022 
- Netframework version (6.0)
- Entity Framework NuGet package

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Installation instructions:

- download the zipped folder (unzip after downloading)
- place the unzipped folder in your repos which can be found on filepath: C:\Users\"your user name"\source\repos
- ensure that microsoft visual studio is installed before launching application, if not, it can be downloaded here: https://visualstudio.microsoft.com/downloads/ (choose the community edition)
- launch program in visual studio 

NuGet Package Installation instructions:

- once you have opened the application visual studio, open the tools dropdown menu and find the NuGet Package Manager
- select "Manage NuGet Packages for Solution"	
- select browse and search for "EntityFramework" by Microsoft
- check the "Solution" checkbox, select the latest version and click the install button below
- navigate to the installed tab and ensure that the EntityFramework has successfully installed
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Instructions for using the application:

The application can be ran through visual studio by opening the project in visual studio

or

You can open the project from the folder itself by going to C:\Users\"your user"\source\repos\POE-PartTwo-ST10084433\POE-PartTwo-ST10084433\bin\Debug
and running the POE-PartTwo-ST10084433.exe file
         
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Frequently Asked Questions:

Q: Will the data persist between runs of the program?

A: Yes, the ability to persist data has now been added.


Q: Can I register more than one account?

A: Yes, you will be able to create multiple accounts although please note that the data between your accounts will only display information relative to each account respectively.


Q: Will I be able to use an older edition of Microsoft Visual Studio?

A: It is recommended that the latest version of Microsoft Visual Studio is installed, it is not guaranteed that older versions will run our program without error.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Contact info: 

Cell no: 084 737 0358

Email: st10084433@vcconnect.edu.za

VC Student number: ST10084433

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Github:

Profile link : https://github.com/Mxttk

Repo link : https://github.com/Mxttk/ST10084433-POE-PartTwo-TimeBankV2

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Code Attribution:

- Drop down Menu : https://youtu.be/dDSFPpNrheI

- Background animation in dropdown menu: https://youtu.be/fOIJzFjx9vs

- How to change cursor type: https://learn.microsoft.com/en-us/dotnet/desktop/wpf/advanced/how-to-change-the-cursor-type?view=netframeworkdesktop-4.8

- Trigger events: https://www.tutorialspoint.com/wpf/wpf_triggers.htm

- Listview Item highlight colour change: https://stackoverflow.com/questions/56991489/how-to-change-a-listviewitems-highlighted-colour-in-wpf

- Error handling for save changes: https://stackoverflow.com/questions/19520022/validation-error-on-savechanges

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Implemented feedback:

- Changed binding of combobox in StudyCalc class from an array to a linq statement that retrieves a list from the database
- Added additional documentation
- Improved upon UML diagram
- Added more advanced feautures under DropdownMenuControl project

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
I hope this guide will assist you in effectively utilising my time management app!
