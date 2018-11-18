#  QA tech challenge - Venkat Bandaru

## Overview
Included in this repository are tests for given for the QA tech challenge, test frameworks and extent report libraries.
Data-Driven Selenium framework based on Page object model provides ability to test Raisin web application. It also adds helper methods for most common functions and builds beautiful, interactive and detailed HTML reports for the tests. Screenshots, tags, devices and machine details are included in the report.

## Documents
1. As requested I have first defined the test cases before preparing the automation test suite. Please refer to the document “Raisin_QA-Challenge-TestCases.xls” under Documents directory in project.
2. Created manual test cases for the “User story 3”. Please refer to the document “Raisin-QA-Challenge_Manual_TestCases.doc” under Documents directory in project.
3. Also proactively I have prepared and attached an automation test report named “Raisin_QA-Challenge-TestReport .doc“ for this whole user stories which will give additional information and insight into how I have approached the tech challenge. 


## Prerequisites
1. Install Java (JDK 8)
2. Java and jar on the PATH (make sure you use java executable from JDK but not JRE)
3. Install Maven and add MAVEN_HOME on the path variable
4. IDE - Eclipse
5. TestNG Eclipse plug-in
6. Install Chrome Browser
7. git bash
8. Chromedriver.exe has already included in project under Webdrivers/

## Maven Dependencies
* Testng 6.10
* Selenium 3.0 or better
* jexcelapi 2.6.12
* com.aventstack.extentreports 3.1.5

## Usage
The following steps will help you run tests:

* Clone the project 
	git clone repo
	
* Using Eclispe:
	1. Open Eclipse -> File -> Import -> Existing Maven projects -> Provide the path of the maven project till pom.xml
	2. Execution of the test scripts 
		Right Click on the pom.xml -> Run As -> maven test
			(or)
		Right Click on the TestNGRunners/RaisinTestSuite.xml -> Run As -> TestNG Suite
	3. Report is generated under the project/reports*<DDHHmmss>*/report.html
	
* Using Command Prompt:
	1. Go to project path(till pom.xml folder) in command prompt/terminal.
	2. provide the below maven command
		mvn test
	3. Report is generated under the project/reports*<DDHHmmss>*/report.html


