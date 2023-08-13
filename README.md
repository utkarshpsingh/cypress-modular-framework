# TestFramework

Modular Test Automation Framework

This Framework is based on Page Object Model using Cypress + TypeScript, 
*  Page Object Model is an object design pattern, where web pages are represented as classes, and the various elements on the page are defined as variables on the class.

*  Cypress is a front-end testing tool for web applications. Cypress runs on Windows, Linux, and macOS. Cypress app is open-source software released under the MIT License while the Cypress Cloud is a web application.

Packages: 


Under src/main/java:

1)  Controller: user interactions as methods are implemented in the classes under this package and the object of these
           classes should be registered in the Application controller to pass the driver instance


2)  Data: This package contains loading data properties from external resources i.e. excel files etc...


3)  Object Repository: PageFactory in Selenium is an extension to Page Object and can be used in various ways. In this case, we will            use Page Factory to initialize web elements that are defined in web page classes or Page Objects

Under src/test/java:

5) Page functions: Function related to the pages of the application

6) Report: Custom extends the report to class.





**Note:**
