## Levels of Testing Software

### Unit Testing

- We test a component or a small module
- Normally it is done by developers at code level
- This is comes under white box testing
- Unit is a single component or module of software
- It conducts on a single program or single module
- Techniques
    - Basis path testing: every path of the program should be executed a least once
    - Control structure testing: verify if this conditional structures and loops structures are working properly
        - Conditional coverage
        - Loops Coverage
    - Mutation testing
        - It is about repetition
        - Testing a code by passing different types of inputs

### Integration Testing

- Integrate multiple components then we check the data flow or communication between modules
- Also under the white box testing
- It performed bewtween 2 or more modules
- It focuses on checking data communication between multiple modules
- It is done by developers at the coding level
- Testers can do Integration Testing at the application level because they don’t have the code but they receive an UI part to test the functionality
- Types
    - Incremental Integration Testing
        - Incrementally adding the modules and testing the data flow between modules
        - 2 approaches
            - Top Down
                - Ensure the module added is the child of the previous module
            - Bottom Up
                - Ensure the module added is the parent of the previous moduler
            - Hybrid approach
                - Combination of both approaches
    - Non-Incremental Integration Testing
        - We integrate all modules at once and test the data flow between modules
        - This options is not recommended because it has drawbacks
            - We might miss data flow between some of the modules
            - If you find any defect we can’t understand the root cause of defect

### System Testing

- We testing overall functionality of the application with respective clients requirements
- It is a black box testing
- It is done by testers
- After complettion of component and integration testing, we start system testing
- Before of this testing, we need to know the customer requirements
- It focuses on below aspects
    - User Interface Testing
        - We test all the UI parts like if they properly aligned, text boxes, check boxes, drop dwons, the colors of the applications, the navigation between pages, data flows
    - Functional Testing
        - Checking login functionality or balance functionality
    - Non-functional testing
        - Security testing, perfomance (speed of the application), installation, compatibility
    - Usability Testing
        - We have to check those user manuals

### User Acceptance Testing (UAT)

- It is done by testers and users
- Conducted by the customers and users
- If everything works find, they will accept the software
- They will verify if the requirements are sastify or not
- Testers can assist customers/users
- UAT Team conducts acceptance testing in two levels
    - Alpha Testing
        - Users/Customers will do the testing and development enviroment
    - Beta testing
        - Users/Customers will do basic testing in their own enviroment.
        - They received the software and install it in their own machine
- After this testing, the software or product goes to a production and then the customers will start using the software