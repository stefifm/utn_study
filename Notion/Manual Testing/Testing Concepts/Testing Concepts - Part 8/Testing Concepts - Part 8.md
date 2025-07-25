## Defect/Bug Cycle

- It is the state of the defect

![[2025-02-21_19_17_05-(1)_Manual_Software_Testing_Training_Part-9_-_YouTube_-_Brave.jpg]]

- Reasons that a bug is rejected
    - Enhancement: in coming versions, there will be implemented as a feature.
    - Need more information: The dev doesn’t understand the bug and needs more information
    - Not Reproducible: The dev can not reproduce the bug in his environment
    - As designed: It is not a bug, it is working as designed

## Test Cycle Closure

- Activities
    - Evaluate cycle completion criteria based on Time, Test Coverage, cost, software, critical business objectives, quality
    - Prepare test metrics based on the above parameters
    - Document the learning out of the project
    - Prepare test summary report
    - Qualitative and quantitative reporting of quality of the work product to the customer
    - Test result analysis to find out the defect distribution by type and severity
- Deliverables
    - Test closure report
    - test metrics

## When to Stop Testing

- Executed all test cases and all them pass
- The application should not have any bugs
- The application can have minors bug but they should not affect the business work flow

## Software Testing Metrics

![[2025-02-21_19_37_50-(1)_Manual_Software_Testing_Training_Part-9_-_YouTube_-_Brave.jpg]]

  

![[2025-02-21_19_40_46-(1)_Manual_Software_Testing_Training_Part-9_-_YouTube_-_Brave.jpg]]

![[2025-02-21_19_42_10-(1)_Manual_Software_Testing_Training_Part-9_-_YouTube_-_Brave.jpg]]

- Defect Leakage: Defect leakage happens when bugs slip through testing and show up later—whether during UAT, in production, or in later development phases. It signals that your testing process has gaps or blind spots that need attention. Think of it like holes in a security net that let issues pass through undetected.

## QA/Testing Activities

- Understanding the requirements and functional specifications of the application
- Identifying required Test Scenario
- Designing Test Cases to validate application
- Setting up Test Environment
- Execute Test Cases to valid application
- Log test results (how many test cases pass/fail)
- Defect reporting and tracking
- Retest fixed defects of previous build
- Perform various types of testing in application
- Reports to Test Lead about the status of assigned tasks
- Participated in regular team meetings
- Creating automation scripts
- Provides recommendation on wheter or not the aplication/system is ready for production

## Principles of Software Testing

1. Start software testing at early stages. Means from the beginning when you get the requirements
2. Test the software in order to find the defects
3. Highly impossible to give the bug free software to the customer
    1. We can not release a 100% qualitive product
4. Should not do Exhaustive testing. Means we should not use same type of data for testing every time
5. Testing is context based. Means decide what types of testing should be conducted based on type of application
6. We should follow the concept of Pesticide Paradox. Means, if you are executing same cases for longer run, they wont be find any defects. We have tomkeep update test cases in every cycle/release in order to find more defects
7. We should follow defect clustering. Means some of the modules contains most of the defects. By experience, we can identify such risky modules. 80% of the problems are found in 20% of the modules.
    1. Defect clustering refers to the idea that, in many software systems, most of the defects (bugs) are often found in just a few areas or components of the software rather than being evenly spread across the entire system. In fact, if you don’t resolve these defects in time, they can lead to cascading defects.
    2. [https://www.linkedin.com/pulse/defect-clustering-software-testing-testrigor-tigbe/](https://www.linkedin.com/pulse/defect-clustering-software-testing-testrigor-tigbe/)