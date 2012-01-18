RhoconnectNET_MVC4_App Sample
===

Sample of complete ASP.NET MVC4 Contact back-end application.
 
Prerequisites:

* .NET 4 framework
* Git
* ASP.NET MVC4 framework.
* Visual Studio 2010

The application uses an embedded in-memory database (Contacts.sdf). 
Using the in-memory database means there is no need to setup and run a separate database server for this application.

To run this application, build it in Visual Studio, create a deployment package (using Project --> Build Deployment Package).
Then, deploy it on the Microsoft's IIS server to run.

Additionally, this repo contains ContactsApp_final project, which has all the completed code that is necessary for integration with Rhoconnect. You can just use the it (you will still need to modify the `set_app_point` with your app endpoints and add the RhoconnectNET library reference to your project.)

