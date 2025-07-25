## System Testing Types

- We are testing the overall function of the application with respective customer’s requirements
- This testing is conducted after the Integration testing
- We have to setup are own testing enviroment

### GUI Testing

- Graphical User Interface is a process of testing the user interface of an application
- A graphical user interface includes all the elements such as menus, checkbox, buttons, colors, fonts, sizes, icons, content and images
- We test the frontend and how is working with the backend

![[2025-02-14_19_35_35-Manual_Software_Testing_Training_Part-4_-_YouTube_-_Brave.jpg]]

### Usability Testing

- During this testing, we validate if the application provided context sensitive help or not to the user
- Checks how easily the users are able to understand and operate the application
- Usability means easy for the user
- We focuses in helped documents
- All kind of applications have to provided a easy manual to the users

### Functional Testing

- Functionality is nothing but behavior of application
    - If the application works acording to the customer requirements
- Functional Testing talks about how your feature should work
- The main focuses is the functionality of the elements
    - In GUI Testing, we test if the checkbox is properly align
    - In Functional Testing, we check if the textbox accepts characters properly or not: textbox requirements indicates that should be allow 8 characters, with special one and a number and we have to verify if this works or not.
- Types of Functional Testing
    - Object Properties
        - Object is an element
        - Every element have have properties
        - For example: the textbox can be enable/disable, in a dropdown I can only select one option
    - Database
        - We need to know SQL
        - It is also a backend testing
        - We need to check if the Data Manipulation Language works properly
        - DML are
            - Select
            - Insert
            - Update
            - Delete
        - Other SQL Languages: [https://www.geeksforgeeks.org/sql-ddl-dql-dml-dcl-tcl-commands/](https://www.geeksforgeeks.org/sql-ddl-dql-dml-dcl-tcl-commands/)
        - This testing combine white and black box testing. It is a gray box testing
        - How we perfom this testing
            - We try to submit the data from the UI
            - Then we login to the database and we check if contents the data or not
        - Other test
            - Table level validations: Size of columns, columns types, column lenght, the relation between tables, SQL Functions, Triggers, Store Procedures,
    - Error Handling
        - We focuses on error message
        - Tester verify the error messages while perfoming incorrect actions on the application
        - Error messages should be readle
        - User understandable/simple language
    - Calculations/Manipulations
        - Test if math calculations in financial applications are working property
        - We focuses on the data
        - Tester should verify the calculations
    - Links Existence and Links Execution
        - Where exactly the links placed: links existence
        - Links are navigating to proper page or not: links execution
        - 3 types of links
            - Internal: We click on the link and we navigate to the same page but in different section
            - External: We click on the link and we navigate to another page
            - Brokens: The link will be there but doesn’t have any action
    - Cookies and Sessions
        - Cookies:
            - when browser save data that comes from the backend server in a cookie to make fast display when we do the same actions. It remember the actions that user has done.
            - Cookies are files or temporary files which are created by the browser while you browsing the pages through the internet
            - They are creating on the client side
        - Sessions
            - They are creating on the server side
            - Sessions are time slots created by the server. And will be expired after some time
            - Test: We browsed to the page and don’t anything for few minutes or seconds, then we try to do some actions and should give a message “session has expired”.

### Non-Functional Testing

- Focus on perfomance, load it can take and security
- It perfoms after the application functionality is stable
- We also focuses on customer expectations
- Types
    - Perfomance Testing: Tester has a dedicated enviroment to perform it. How the application responds, the speed of the application
        - Load Testing: we increase slowly the load and verify the respond time of the application
        - Stress Testing: Suddenly increase/decrease the load of the application and check the speed of the application
        - Volume Testing: how much data is able to handle by the application
    - Security Testing: how secure is our application. We have to check
        - Authentication: Users are valid or not
        - Autherization/Access control: if the user valid have access to some things of the application. We verify the permissions of the valid user
    - Recovery Testing: The capability of the application to recover from a problem. We check the system change to abnormal to normal state
    - Compatibility Testing: If your application is working find in different enviroments.
        - Forward: When the behavior and compatibility of software or hardware are checked with its newer version
        - Backward: When the behavior and compatibility of software or hardware are checked with its older version
        - Hardware: Checking compatibility with a particular size of RAM, ROM, Hard Disk, Memory Cards, Processor, Graphics Card
    - Configuration Testing
    - Installation Testing: testing the installation process. We have to check screens are clear to understand, the screens navigation. And also, we have to check the uninstallation process.
    - Sanitation/Garbage Testing: We have to check if the application has an extra functionality which doesn’t apply with the customer requirements. If any application provides extra features/functionality then we consider them as a bug.

![[2025-02-15_20_44_35-Manual_Software_Testing_Training_Part-4_-_YouTube_-_Brave.jpg]]