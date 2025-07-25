## Test Plan

- It’s a document that describes the test scope, test strategy, objectives, schedule, deliverables and resources required to perform testing for a software product
- We have to specify what’re we going to test, what are not going to test
- Test plan template contents
    - Overview
    - Scope
        - Inclusions
        - Test Enviroments
        - Exclusions
    - Test Strategy
    - Defect Report Procedure
    - Roles/Responsibilities
    - Test Schedule
    - Test Deliverables
    - Pricing
    - Entry and Exit Criteria
    - Suspension and Resumption Criteria
    - Tools
    - Risks and Mitigations
    - Approvals

## Use Case vs Test Scenario vs Test Case

### Use Case

- Use Case describes the requirement
- It contains three items
    - Actor: which is the user, which can be a single person or a group of people, interacting with process
    - Action: which is to reach the final outcome
    - Goal/Outcome: which is the succesful user outcome
- Prepared by Business Analyst

![[2025-02-20_19_17_41-(1)_Manual_Software_Testing_Training_Part-8_-_YouTube_-_Brave.jpg]]

### Test Scenario

- A possible area to be tested (what to test)

![[2025-02-20_19_19_56-(1)_Manual_Software_Testing_Training_Part-8_-_YouTube_-_Brave.jpg]]

### Test Cases

- Step by step actions to be performed to validate functionality of AUT(How to test)
- Test case contains test steps, expected result and actual result
- Prepared by Test Engineer
- A test case is a set of actions executed to validate particular feature or functionality of your software application

### Test Suite

- It’s a group of test cases which belongs to same category

![[2025-02-20_19_21_27-(1)_Manual_Software_Testing_Training_Part-8_-_YouTube_-_Brave.jpg]]

## Test Case Template

- Test Case Contents
    - Test Case ID
    - Test Case Title
    - Description
    - Pre-Condition
    - Priority Order(P0, P1, P2, P3)
    - Requirement ID
    - Step/Actions
    - Expected Result
    - Actual Result
    - Test Data

![[2025-02-20_19_28_09-(1)_Manual_Software_Testing_Training_Part-8_-_YouTube_-_Brave.jpg]]

## RTM or Requirement Traceability Matrix

- RTM describes the mapping of Requirements with the test cases
- The main purpose of RTM is to see that all test cases are covered so that no functionality should miss while doing software testing
- RTM Parameters Include
    - Requirement ID
    - Req Description
    - Test Case IDs

![[2025-02-20_19_33_14-(1)_Manual_Software_Testing_Training_Part-8_-_YouTube_-_Brave.jpg]]

## Test Environment Setup and Test Execution

### Test Environment

- Test Environment is a plataform specially build for test case execution on the software product
- It is created by integrating the required software and hardware along with proper network configurations
- Test Environment simulates production/real tiem environment
- Another name of test environment is Test Bed
    - Software and Hardware environment we create to perform the testing
- Understand the customer requirement and exactly we have to replicate that enviroment in the testing

### Test Execution

- During this phase will carry out the testing based on the test plans and the test cases prepared
- Entry Criteria: test cases, test data and test plan
- Activities
    - Test cases are executed based on the test planning
    - Status of test cases are marked, like Passed, Failed, Blocked, Run, and others
    - Documentation of test results and log defects for failed cases is done
    - All the blocked and failed test cases are assigned bug ids
    - Retesting once the defects are fixed
    - Defects are tracked till closure
- Deliverables: Provides defect and test case execution report with completd results

### Guidelines for Test Execution

- The build being deployed to the QA environment is the most important part of the test execution cycle
- Test execution is done in QA environment
- Test execution happens in multiple cycles
- Test execution phase consists Executing the test cases + test scripts (if automation)

## Defects/Bug

- Any mismatched functionality found in an application is called as Defect/Bug/Issue
- During Test Execution, Test engineers are reporting mismatches as defects to developers through templates or using tools
- Defect Reporting Tools
    - Clear Quest
    - DevTrack
    - Jira
    - Quality Center
    - Bug Jilla
    - etc

## Defect Report Contents

- Defect ID: Unique id number for the defect
- Defect Description: Detailed description of the defect including information about the module in which defect was found
- Version: Version of the application which defect was found
- Steps: Detailed steps along with screenshots with which the developer can reproduce the defects
- Date Raised: Date when the defect is raised
- Reference: where you Provide reference to the documents like requirements, design, architecture or may be even screenshots of the error to help understand the defect
- Detected By: Name/ID of the tester who raised the defect
- Status: Status of the defect
- Fixed by: Name/ID of the developer who fixed it
- Date Closed: Date when the defect is closed
- Severity: which describes the impact of the defect on the application
- Priority: which is related to defect fixing urgency. Severity Priority could be High/Medium/Low based on the impact urgency which the defect should be fixed respectively

## Defect Classification (Severity and Priority)

![[2025-02-21_18_31_24-(1)_Manual_Software_Testing_Training_Part-8_-_YouTube_-_Brave.jpg]]

### Severity

- Severity describes the seriousness of the defect and how much impact on Business workflow
- Defect severity can be categorized into four classes
    - Blocker (Show Stopper): This defect indicates nothing can proceed further
        - Login not worked, application crashed
    - Critical: The main/basic functionality is not working. Customer business workflow is broken. They can not proceed further
        - Fund transfer is not working in net banking
        - Ordering product in ecommerce application is not working
    - Major: It cause undesirable behavior, but the feature/application is still functional
        - After sending email, there is no confirm message
        - After booking cab, there is no confirmation
    - Minor: It won’t cause any major break-down of the system
        - Look and feel issues, spellings, alignments

### Priority

- Priority describes the importance of the defect
- How soon the defect should be fixed
- Defect priority states the order in which a defect should be fixed
- Defect priority can be categorized into three classes
    - P0 (High): The defect must be resolved immediately as it affects the system severely and can not be used until it is fixed
    - P1 (Medium): It can wait until a new versions/builds is created
    - P3 (Low): Developer can fix it in later releases

### After

- After reporting this, priority can be changed by your leads or test manager or project managers
- But nobody can change the severity. That is a tester responsibility

### Example of High priority, High severity, Low priority and Low severity

![[2025-02-21_19_03_48-(1)_Manual_Software_Testing_Training_Part-8_-_YouTube_-_Brave.jpg]]

![[2025-02-21_19_10_20-(1)_Manual_Software_Testing_Training_Part-8_-_YouTube_-_Brave.jpg]]

## Defect Resolution

- After receiving the defect report from the testing team, development team conduct a review meeting to fix defects. Then they send a Resolution Type to the testing team for futher coomunication
- Resolution Types
    - Accept
    - Reject
    - Duplicate
    - Enhancement
    - Need more information
    - Not Reproducible
    - Fixed
    - As Designed