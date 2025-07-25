## Test Design Techniques

- We will use it to prepare data for testing.
- We can use less data and improve the coverage in case when we need to use so many data
- Test Design Techniques are to prepare data which will cover each every area of the feature
- Test Design Techniques will be used to reduce the data and increase the coverage
- It helps to design better test cases
- Reduce the number of test cases to be executed
- Important elements:
    - Data: We have to prepare different combinations of data
    - Coverage: We have to cover all scenarios with the combinations of data

### Types of Test Design Techniques

> [!important] **Equivalence Class Partitioning (ECP)**
> 
> - Partition data into various classes and we can select data according to class then test. It reduce the number of test cases and saves time for testing
> - Value check
> - Clasify/partition the data in to multiple classes
> 
> ![[2025-02-19_18_37_18-(1)_Manual_Software_Testing_Training_Part-6_-_YouTube_-_Brave.jpg]]
> 
> ![[2025-02-19_18_43_17-(1)_Manual_Software_Testing_Training_Part-6_-_YouTube_-_Brave.jpg]]

> [!important] **Boundary Value Analysis (BVA)**
> 
> - We focuses on the boundary of the value
> - It is use to check boundaries of the input
> - The paramaters
>     - Min
>     - Min-1
>     - Min+1
>     - Max
>     - Max-1
>     - Max+1
> 
> ![[2025-02-19_18_47_07-(1)_Manual_Software_Testing_Training_Part-6_-_YouTube_-_Brave.jpg]]

> **Input Domain Testing**

- We will use ECP and BVA
- We will verify if the value in the text box/input fields are valid or not

> [!important] **Decision Table based testing**
> 
> - It’s also called as Cause-Effect Table
> - This technique will be used if we have more conditions and corresponding actions
> - In decision table technique, we deal with combinations of inputs
> - To identify the test cases with decision table, we consider conditions and actions
> - If we have more number of conditions/actions then we use decision table
> 
> ![[2025-02-19_19_19_13-(1)_Manual_Software_Testing_Training_Part-6_-_YouTube_-_Brave.jpg]]
> 
> ![[2025-02-19_19_21_13-(1)_Manual_Software_Testing_Training_Part-6_-_YouTube_-_Brave.jpg]]
> 
> - Test Case 1 is a valid test case
> - TC2, TC3 and TC4 are negative test case
> - TC5 is an invalid test case

  

> [!important] **State Transition**
> 
> - In this technique, changes in inputs conditions change the state of the application
> - It allows the tester to test the behavior of an application
> - The tester can perform this action by entering various input conditions in a sequence
> - The testing team provides positive as well as negative input test values for evaluating the system behavior
> 
> ![[2025-02-19_19_32_37-(1)_Manual_Software_Testing_Training_Part-6_-_YouTube_-_Brave.jpg]]

> [!important] **Error Guessing**
> 
> - It is used to find bugs in a software application based on tester’s prior experience
> - We don’t follow any specific rules
> - It depends on tester analytical skills and experience
> - Some of the examples are
>     - Submitting a form without entering values
>     - Entering invalid values suchs as entering alphabets in the numeric field