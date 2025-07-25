## Software

- Software is a collection of computer programs that help us to perform a task
- Types of SW
    - System software: drivers, OS, servers, utilities
    - Programming Software: compilers, debuggers, interpreters. Made by developers
    - Application Software: Web application, Mobile apps, desktop applications: using by users

  

X Bank: autometed the process ——> IT Company ——> understand the requieremnts and develop —→ test —→ deliver a quality product without bugs and free of failures —→ X Bank

- Testing is part of the development process

## What is software testing

- Is a part of a software development process
- Is an activity to detect and identify the defects in the software
- The objective of testing is to release quality product to the client

## What is software quality

Needs to satisfy the next parameters

- Bug-free
- Delivered on time
- Within budget
- Meets requirements and/or expectations
- Maintainable

## Project vs Product

- Project: If software application is developed for specific costumer based on the requirement
- Product: if software application is developed for multiple customers based on market requierements

## Why do we need testing

- Release quality product to the customer
- Software should be bug free and should meets customer requierements

## Error, Bug and Failure

- Error: human mistake - an incorrect human action
- Bug: Deviation from the expected behavior to the actual behavior of the system.
- Failure: The deviation identified by end-user while using the system

## Why the software has bugs

- Miscommunication or no communication
- Software complexity
- Programming errors
- Changing requirements
- Lack of skilled testers

## SDLC

- Software development life cycle
- Is a process used by software industry to design, develop and test the software
- It is a step by step process which we have to follow to develop test and deliver the software to the customer

### 3 Pilars of a company

- People
- Process
- Product

### Stage of SDLC

1. Requirements analysis: We have to collect the requirements from the customer. Understand the requirements. PM will be involved in this phase
2. Design: The designers will design the software. How it should look like?
3. Development: the coding part
4. Testing: test the software before deliver it to the customer
5. Maintenance: deploy it in customer enviroment and maintenance

### Prototype model

- Blue print of the software

### Modules

- It is a simple component of the software

## Verification / Validation

- Verification: checks wheter we are building the right product
    - Software is not ready yet
    - Focus on documentation
    - Static testing
        - Testing the project related documents is called as static testing
        - Review, walkthrough and inspection
- Validation: checks wheter we are building the product right
    - Software is ready
    - Takes place after verifications are completed
    - Focus on software
    - Dynamic testing
        - Unit testing, integration, system testing, UAT testing
        - Testing the actual software
        - Unit testing and integration are done by the developers
        - System testing is done by testers
        - User Acceptance Testing (UAT) is done by testers, users and customers

[https://drive.google.com/file/d/1dm9ANJB0y37NjDHSAOQabgf1vRysQvrP/view](https://drive.google.com/file/d/1dm9ANJB0y37NjDHSAOQabgf1vRysQvrP/view)

## White Box vs Black Box testing methods

- White Box
    - We have to test the internal logic of the program
    - Developers write the code and test it directly
    - We can see what is there internally
    - Only developers can do that
- Black box
    - We can verify the functionality of
        - test
        - application or software
    - We don’t need to know the internal logic of the program
    - We need to know the functionality, how the flows are working, check the ui
    - These testing method is for testers

## Statict Testing Techniques

### 1) Review

- Check the entire document whether it is completely or not
- Check if the contents of the document are correct or not
- Conducts on documents to ensure correctness and completeness
- Types of review
    - Requirement Reviews
        - Review the requirements from the clients to understand better
    - Design Reviews
        - Review of the design of the program
    - Code Reviews
        - Check if the code is right
        - This job is done by the developers itself
    - Test Plan Reviews
        - Done by testers
    - Test Cases Reviews
        - Done by testers
    - Etc

### 2) Walkthrough

- It is also a kind of review which is informal
- We don’t have a specific plan and we don’t have a specific meeting
- Author reads the documents or code and discuss with peers
- It’s no pre-planned and can be done whenever required
- Also, it doesn’t have minutes of the meet
- It can be done by many people, everytime and any place

### 3) Inspection

- Is more formal review type
- We have a pre-plan
- In which a least 3-8 people will sit in the meeting and 3 kind people will be involved
    - reader: is the author of the document
    - writer: he will note of the questions and clarifications from the team
    - moderator: He is like a mediator of the meeting
    - plus concerned
- Inspection will have a proper schedule which will be intimated by email to the concerned developer/tester

## Dynamic testing techniques

### Unit Testing

- Developers will concentrate on testing the code

### Integration testing

- They will integrate multiple modules and multiple components
- They will check the data flow between the components

### System testing

- Testers check if the software is working according to customer requirement
- They check if functionality perfom correctly

### UAT (User Acceptance Testing)

- They will set up the exact enviroment where the customer is going to work and they install the software and from the customer point of view, they will test some flows

## QA (Quality Assurance), QC (Quality Control ) and QE (Quality Engineering)

### QA vs QC

- QA is process related
    - The people who are belongs to the qa will alwas define the process and talk about the process
    - They ensure that the rest of the people are profiling proper for process properly
    - They care about every steps of the SDLC process
    - They focus on building in quality
        - We try to build the quality product
        - Follow certain process properly
    - QA is preventing defects
        - If we follow the process correctly or perfectly, we can prevent the defects in the future
    - QA is process oriented
    - QA for entire life cycle
- QC is the actual testing the software
    - They are involved only during the testing part of the SDLC
    - They test the software
    - They talk about the people
    - They focus on testing for quality
        - To deliver the quality product to the customer
        - To find bugs
    - QC is detecting defects
        - We will find the defects
    - QC is product oriented
    - QC for testing part in SDLC

### Quality Engineering (QE)

- They write the code for testing the software
- They perfom automation test
- QC perfom manual testing and automation testing in some cases