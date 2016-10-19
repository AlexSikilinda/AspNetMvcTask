# Goal:
Develop basic functionality of ASP.NET MVC application with data access layer

# Task:
Create an application which automatizes hospital business processes. There are two main entities: doctors
and patients. There are also some additional helper tables which contain link between doctors and patients,
patients statuses etc.
We have basic DB design (please see corresponding lecture). Feel free to adjust or change it if you think
it is sensible, but keep in mind that the DB must be in 3rd normal form.
All user input should be validated at least on server side.
DAL is implemented using Entity Framework and "Repository" pattern (https://msdn.microsoft.com/en-us/library/ff649690.aspx). 

The app should allow users to:

1. see list of all doctors
2. search doctors by name
3. add new doctors
4. edit existing doctors
5. delete doctors (with confifrmation)
6. list all patients
7. search patients by name
8. add new patients
9. edit patients (including changing patient status with dropdown)
10. assign doctors to patients
11. delete patients (with confirmation)

# Advanced tasks (desirable but not obligatory):

1. use dependency injection to inject dependencies
2. write unit tests which covers all logic (see Freeman first chapter to get idea how to do it)
3. reimplement repositories using pure ADO.NET
4. add role based authorization (doctors can do anything, patients can only view their own data)
5. implement remote validation (https://msdn.microsoft.com/en-us/library/gg508808(VS.98).aspx)
6. implement filtration for users
7. implement filtration for doctors
8. add ability to store user photo
9. add ability to store user desease history
10. implement confirmation dialogs with jQuery
11. feel free to ask me for additional tasks if you have finished all above :)

# Resources:
* https://www.asp.net/mvc/overview/getting-started/introduction/getting-started
* http://pluralsight.com/training/Player?author=scott-allen&name=aspdotnet-mvc5-fundamentals-m1-introduction&mode=live&clip=0&course=aspdotnet-mvc5-fundamentals
* https://www.asp.net/mvc/overview/getting-started/getting-started-with-ef-using-mvc/creating-an-entity-framework-data-model-for-an-asp-net-mvc-application
* https://mva.microsoft.com/en-us/training-courses/html5-css3-fundamentals-development-for-absolute-beginners-14207?l=Y4COscFfB_7500115888

# Books:
* Pro ASP.NET MVC 4 4th ed. Edition Adam Freeman, Steven Sanderson
* Professional ASP.NET MVC 4 Jon Galloway, Phil Haack, Brad Wilson, K. Scott Allen
