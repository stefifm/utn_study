## Regression Testing

- Tester verify if the second Build has the same bug finded in the first bug and if the modules are afected
- Testing conducts on modified build to make sure there will not be impact on existing functionality because of changes like adding/deleting/modifying features
- Types
    - Unit regression testing: testing only the changes/modifications done by the developer
    - Regional regression testing
        - Testing the modified module along with the impact modules
        - Impact Analysis meeting conducts to identify impacted modules with QA and Dev
    - Full regression testing
        - Testing the main feature and remaining part of the application
        - Example: Dev has done changes in many modules, instead of identifying impacted modules, we perform one round of full regression

## Re-Testing

- We have to conduct a test again and again
- We test a functionality which was previously tested, whether is working or not
- In Regression testing we will conduct a test no just in the same functionality but also in the others functionalities
- Whenever the developer fixed a bug, tester will test the bug fix
- Tester close the bug if it worked otherwise re-open and send to developer
- To ensure that the defects which were found and posted in the earlier build were fixed or not in the current build
- Example
    - Build 1.0 was released. Test team found some defects (Defect id 1.0.1, 1.0.2)
    - Build 1.1 was released, now testing the defects 1.0.1 and 1.0.2 in this build is retesting

![[2025-02-18_11_25_34-Manual_Software_Testing_Training_Part-5_-_YouTube_-_Brave.jpg]]

## Smoke and Sanity Testing

- Smoke and Sanity testing come into the picture after build release
- Build is a peace of the software that contains multiple features
- **Smoke Testing**
    - Tester will do some basic functionality testing, he will not go in depth
    - Basic functionality testing: tester verify if he has the complete build or not, if the installation is working or not, if the build is stable or not
    - Tester focus in that specific build
    - The build always is unstable so smoke testing testing will conduct in every build
    - It is the first test that we have to conduct
- **Sanity Testing**
    - After many cycles, the build becomes stable. In that case, will conduct the sanity testing
    - It is mainly focuses on fuctionalities
        - Not just build installation, navigation
        - But also checking the mainly functionalities like login is working, links are working

![[2025-02-18_11_29_17-Manual_Software_Testing_Training_Part-5_-_YouTube_-_Brave.jpg]]

![[2025-02-19_09_53_29-(1)_Manual_Software_Testing_Training_Part-5_-_YouTube_-_Brave.jpg]]

## Exploratory Testing

- We have to explore the application, understand completely and test it
- Understand application, identify all possible scenarios, document it then use it for testing
- We do exploratory testing when the application is ready but there is no requirement
- Test Engineer will do exploratory testing when there is not requirement
- Drawbacks
    - You might misunderstand any feauture as a bug or any bug as a feauture since you don’t have requirement
    - Time consuming
    - If there is any bugin application, you will never know about it

## Adhoc Testing

- Testing application randomly without any test cases or any business requirement document
- It is an informal testing type with an aim to break the system: find the corner defects of the application
- Tester should have knowledge of application even thou he doesn’t have requirements/test cases base on previous experience
    - You know some functionalities like login works, add products to the card
- This testing is usually an unplanned activity
- Also we can conduct this testing to find the corner scenarios: while you use the application some where which is not identifibly

## Monkey Testing

- Testing application randomly without any test cases or any business requirement
- Tester don’t have knowledge of application
- Suitable for gaming applications

  

## Adhoc vs Exploratory vs Monkey

![[2025-02-19_10_40_26-(1)_Manual_Software_Testing_Training_Part-5_-_YouTube_-_Brave.jpg]]

### Corner Case

- corner case is when multiple parameters are simultaneously at extreme levels, and the user has put a corner of the configuration space.
- There are also errors that can result in two abnormalities, this is often called two edge cases combine: For example, audio speakers at maximum volume distort the audio, at the same time there is feedback from the microphone it can result in system failure.
- Causes
    -  **The user enters a value of 0**, if the user does this it will cause the invoice to be invalid.
    - **Users do the same thing**, if there are 1000 other users doing the same thing and at the same time, it can cause corner cases.
    - **The system is overloaded**, if a system is overloaded then the system cannot process all the work it has.

### Edge cases

- An edge case is a problem that occurs at the extreme (maximum or minimum) in the operating parameters. Edge cases are rarely encountered by users.
- Causes
    -  **Application crashes**, this case is the most common case without an obvious.
    - **It takes a long time to load the page**, in this case, it usually takes 5 seconds or more to load part of the application or website.
    -  **Audio problem**, usually the audio won’t play in the background after the video screen is closed occasionally.

## Positive and Negative Testing

### Positive Testing

- Testing the application with ==valid inputs==
- It checks whether an application behaves as expected with positive inputs
- For example:
    - Enter Only Numbers: ==9999== ——→ ==Positive Testing==
    - There is a text box in an application which can accept only numbers. Entering values up to 9999 will be acceptable by the system and any other values apart from this should not be acceptable
    - To do a positive testing, set valid inputs values from 0 to 99999 and chech whether the system is accepting values

### Negative Testing

- Testing the application with ==invalid inputs==
- It checks whether an application behaves as expected with negative inputs
- For example
    - Enter Only Numbers: ==abcdfg== ——> ==Negative Testing==
    - Negative testing can be performed by entering characters A to Z of from a to z
    - Either software system should not accept the values or else it should throw an error message for these invalid data inputs

![[2025-02-19_12_18_12-(1)_Manual_Software_Testing_Training_Part-5_-_YouTube_-_Brave.jpg]]

## End-to-End Testing

- Testing the overall functionalities of the system including the data integration among all the modules
- We checks all components in one flow
- It should covert every flow of the application
- We should covert the main functionalities of the application

![[2025-02-19_12_20_14-(1)_Manual_Software_Testing_Training_Part-5_-_YouTube_-_Brave.jpg]]

## Globalization and Localization Testing

### Globalization Testing

- Performed to ensure the system or software application can run in any cultural or local enviroment
- Different aspects of the software application are tested to ensure that it supports every language and different attributes
- It tests the different currency formats, mobile number formats and address formats are supported by the application
- For example, Facebook supports many of the languages and t can be accessed by people of different countries. Hence it is a globalized product

### Localization Testing

- Performed to check system or software application for a specific geographical and cultural enviroment
- Localized product only supports the specific kind of language and is usuable only in specific region
- It testes the specific currency format, mobile number format and address format is working properly or not
- For example, Baidu supports only the Chineses language and can be accessed only by people of few countries. Hence it is a localized product.