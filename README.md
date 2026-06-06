

# TestNG - Test New Genaration 
Java Based Unit Testing Tools

# Advantages:
1.  Test Cases & Test Suites.
2.  Grouping of Test Cases.
3.  Priotize.
4.  Parameterization.
5.  Parallel Testing.
6.  Reports.


# TestNG Comfig ----->
1. Install Testing on IntelliJ IDEA
2. add testing library to build path/add testing dependecy on pom.XML

        <!-- Source: https://mvnrepository.com/artifact/org.testng/testng -->
        <dependency>
            <groupId>org.testng</groupId>
            <artifactId>testng</artifactId>
            <version>7.12.0</version>
            <scope>test</scope>
        </dependency>


# --------------------@Test Annotation------------
1. TestNG execute Test Method Based on Alphabetic Order.
2. @Test (Priority=num) controls the order of execution.
3. Once you provide the Priority to the test methods, the order of methods is not consider.
4. priorities can be random number.
5. If you don't provide any priority, by Default value is zero.
6. If the Priorities are same then execute methods on alphabetical order.
7. Negative Values are acceptable in priority.
8. TestNG execute test methods only if they are having @Test Annotation.


Execute Test cases using testing .xml file
test xml file
# ------------

1. Genarate Automatically.
2. Manually.

Test Suites---->test cases---->test steps
xml file---->class---->test methods

#

2 things Achived from xml
1. Execute gorup of test cases as a 1 suites.
2. We can genarate testing reports (default)

















