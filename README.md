# AngularJS sample in HCP

##What is it?

This ia a sample HTML5 application that demonstrates the ease of using JavaScript frameworks like AngularJS and Bootstrap 
for UI development in the SAP HANA Cloud Platform.

The application displays invoices from the [standard Northwind OData services](http://services.odata.org/V4/Northwind/Northwind.svc/)

- Angular JS as the client side framework that helps in development of UI applications by providing MVC/MVVM features,data binding etc.
- The Northwind OData service as the back-end service for fetching data (of course any RESTful API can be used here, not necessarily an OData service).
- Bootstrap as the client side framework for styling the application.


## How to run it?

##### Step 1: Clone the repository 

Clone the repository or download the repository ZIP. If you download the repository as a ZIP file, unzip it. 

##### Step 2: Create a project archive.
Within the repository folder, right click on the angularnorthwindprj folder and create an archive file named angularnorthwindprj.zip.

##### Step 3: Import project into HCP

Import this [archive as an HTML5 application in the HCP cockpit](https://help.hana.ondemand.com/help/frameset.htm?b8d879c30b44455d906bfa4c35b8221d.html). 
During import, provide the application name as "angularnorthwindprj" and version name as "1.0".

##### Step 4: Activate this version
[Activate this version](https://help.hana.ondemand.com/help/frameset.htm?dfaaf837ca5f4ff8bb25907a342a1416.html).
 
##### Step 5: Set the destination in HCP
Import the destination file available at angularnorthwindprj/destination/northwind [into the HCP cockpit](https://help.hana.ondemand.com/help/frameset.htm?a2550c3fcf2b430f94f99072677bf9ec.html).
 
##### Accessing the application
Launch the application that is accessible on the URL: <BR>
`https://angularnorthwindprj-pXXXXXtrial.dispatcher.hanatrial.ondemand.com`

Replace 'pXXXXX' with your SCN user ID.









