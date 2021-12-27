# QA_Assignment_Flink

Overview:
Test is created with Cucumber + Spring Boot framework. This framework helps to maintain the code resuablity and reliability.

Folder Structure:
1. annotations folder contains the grouping of annotations which has been used in the java classes as dependency injections
2. basePage folder contains common selenium actions
3. config folder contains the Driver, Locators and Application property configurations
4. dataProvider folder contains the global variable which can be reused across the test
5. StepDefinition folder contains the cucumber glue step definition methods related to feature file
6. resources folder contains the application details and locator used for the tests
7. features folder contains the feature of the test which we need to test
8. Runner folder contains the execution class for the cucumber + spring boot framework


Things to Know before Triggering execution:
1. Import project as maven and install Cucumber Plugin, Junit, lombok
2. Rebuild the pom.xml to add all the dependencies in local
3. Runner class is the triggering point of the execution
4. Driver versions may vary, so kindly install the specified driver to see the execution
5. If you are running the test from eclipse kindly use eclipse photo or above to avoid compatibility issue of spring framework(recommended: Intellij)
6. Install lombok plugin in eclipse to avoid data provider error
