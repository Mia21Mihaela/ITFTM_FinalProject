# ITFTM_FinalProject

This is the final project of the itFactory Manual Testing course. The scope of the final project is to utilize all the new developed skills in the corse and practice them on a live application.
---
## Revision History

| Date  | Description  | Author | Comments | 
|---|---|---|---|
| 05.05.2023 | Test Plan | Mihaela Lisman |   |


## Table of content

**1. Introduction**
     
      1.1 Project Objective
     
      1.2 Functionalities in scope
     
      1.3 Functionalities and tests out of scope

  **2. Test process**
     
      2.1 Test planning
     
      2.2 Test analysis
     
      2.3 Test design
     
      2.4 Test implementation
     
      2.5 Test execution
     
      2.6 Test closure
     
      2.7 Test monitoring and control

  **3. Test deliverables**
     
      3.1 Test plan
     
      3.2 Test conditions
     
      3.3 Test cases
     
      3.4 Daily test summary reports
     
      3.5 Traceability matrix
     
      3.6 Test case results
     
      3.7 Bugs report
     
      3.8 Test completion report

 -------

 ## 1. Introduction
<p> &nbsp;&nbsp;&nbsp;<strong>OpenCart</strong> is free open source e-commerce platform for online merchants. The application provides a professional and reliable foundation from which to build a successful online store. This foundation appeals to a wide variety of users; ranging from <em>seasoned web developers</em> looking for a user-friendly interface to use, to <em>shop owners</em> just launching their business online for the first time. OpenCart has an extensive amount of features that gives you a strong hold over the customization of your store. With <strong>OpenCart</strong>'s tools, you can <em><strong>help your online shop live up to its fullest potential.</em></strong></p>
<p>&nbsp;&nbsp;&nbsp;<strong>OpenCart's administration</strong> side of the store is where you can <em><strong>modify features</em></strong>, <em><strong>upload images</em></strong>, <em><strong>add products</em></strong>, <em><strong>keep track of customers</em></strong>, <em><strong>manage payments</em></strong>, and much more. Customization in the admin affects how the customer will interact with a store: by modifying the look, structure, and content of the store front.</p>

### 1.1 Project Objective
<p> We need to raise the trust in the quality of the project as high as possible before releasing it to customers. </p>
<p> The scope of the final project for ITF Manual Testing Course is to use all gained knowledge through the course and apply them in practice, using an available application. </p>


Application under test: [OpenCart Admin Interface](https://demo.opencart.com/admin) and [OpenCart Website](https://demo.opencart.com/)<br>
Application Documentation can be found [here](http://docs.opencart.com/en-gb/introduction/)

### 1.2  Functionalities in scope
The functionalities that are going to be tested are:
* accessing the admin panel with an existing admin account
* accessing your store from the admin panel
* ability to search products on the website
* registering on the website with valid personal information

Testing types used: 
* functional testing
* GUI testing
* positive testing
* negative testing
* experience based testing
* cross-browser testing

### 1.3 Functionalities and tests out of scope
* The features out of scope: Security settings, Security Improvements
* Non-functional testing like stress, performance is beyond scope of this project.
* No QA support for mobile applications developed. Only web applications will be tested.
* Automation testing is beyond scope.

## 2. Test process

### 2.1 Test planing
***Roles and responsabilities***

| Role  | Name  | Task/Work | 
|---|---|---|
| Tester | Mihaela Lisman  | will test: accessing your store from the admin panel and the ability to search products on the website  | 
| Tester | Andrei Pop | will test: the process of accessing the admin panel using an existing account and registering on the website with valid personal information|

***Entry criteria***
* functional business specifications are defined
* roles needed for the project are allocated
* testing environment is up and running
* smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing)

***Exit criteria:***
* all test cases have been executed 
* 90% of tests are passed
* no Critical issues/bugs have Open status (All unresolved bugs have low priority and low severity)
* exploratory testing performed on the features: login to the admin panel, logout of the admin panel, dashboard, add new store, edit store
* update tests are 100% passed (update tests will not generate other new issues that impact the application)

***Risks:***
* user data (banking related data, funds, transactions, etc) might be impacted with update tests
* stability risks (crashes, disconnects, SSL certificate expiration, server issues, API problems)
* IE browser might have performance issues
* the web page pagination could be impacted when opened on mobile devices
* stress conditions might impact the web application
* new browser might not be supported
* lack of personnel resources
* late delivery of the product

### 2.2 Test analysis
The testing process will be done based on the requirements for features: 
* accessing the admin panel with an existing admin account
* accessing your store from the admin panel
* ability to search products on the website
* registering on the website with valid personal information

We plan on running a full regression test on the current version of the aplication.

### 2.3 Test design
* All the test cases are written and reviewed 
* Functional test cases will be created in Zephyr Squad using Jira as Test Management tool
* GUI test cases will be created in Zephyr Squad using Jira as Test Management tool
* Positive testing test cases will be created in Zephyr Squad using Jira as Test Management tool
* Negative testing test cases will be created in Zephyr Squad using Jira as Test Management tool
* Regression testing test cases will be created in Zephyr Squad using Jira as Test Management tool
* Cross-browser testing test cases will be created in Zephyr Squad using Jira as Test Management tool
* Experience based testing test cases will be created in Zephyr Squad using Jira as Test Management tool

### 2.4 Test implementation
* All the test data is available and reviewed (admin account: username=demo, password=demo; different type of currency: US dollar, euro and pound sterling)
* This test run includes only regression testing in which we will run tests that have the highest priority, this will be main priority
* Cycle summary was created and test cases were added to the cycle summary 
* Test environment is up and running: [OpenCart Admin Interface](https://demo.opencart.com/admin) and [OpenCart Website](https://demo.opencart.com/)

### 2.5 Test execution
* The tests will be executed on the top 4 used browsers: Chrome, Mozilla Firefox, Microsoft Edge, Apple Safari. If time will be available we will extend tests on Opera and Brave browsers
* Test cases will be executed on the created Test Cycle Summary 
* Bugs will be reported based on the failed tests

### 2.6 Test closure
* At least 90% of tests are passed
* No Critical issues have <em>Open</em> status
* Exploratory testing have been performed

### 2.7 Test monitoring and control
* Various periodic reports (daily/weekly/bi-weekly) will be generated to reflect the current status of the testing process. 

## 3. Test deliverables

### 3.1 [Test plan](https://github.com/Mia21Mihaela/ITFTM_FinalProject)
The Test Plan is designed to describe all the details of testing for the following features for OpenCart Admin Interface 
* accessing the admin panel with an existing admin account
* accessing your store from the admin panel
* ability to search products on the website
* registering on the website with valid personal information

The plan identifies the items and the features to be tested, the type of testing to be performed, the roles and responsibilities for testing process, the risks associated with the plan, the resources and schedule required to complete testing.

### 3.2 Test conditions
* we will use test environment
* testing using new accounts and older account is necessary
* The following test conditions could be found here: ***vom adauga link catre document cu test conditions create si incarcate pe github. Test conditions vor fi exportate din Jira.***

### 3.3 Test cases
* The test cases with steps could be found [here](https://github.com/MihaelaLisman/ITFTM_FinalProject/blob/main/ZFJ-issue-export-08-30-2023-242ac113-0001.xlsx).

### 3.4 Daily/Weekly/Bi-weekly test summary report
* link to daily test summary report (number of tests ran today, % of them failed, passed, re-test, etc) ***vom adauga link catre screenshot cu cu test summary report incarcat pe github SAU incarcam imaginea cu raportul direct pe github. Raportul va fi generat din Jira pe masura ce executam test caseurile.***


### 3.5 Traceability matrix
Traceability matrix can be found [here](https://github.com/MihaelaLisman/ITFTM_FinalProject/blob/main/Forward%20Traceability_30_8_2023.xlsx).

### 3.6 Test case results
* The test cases results could be found here: ***vom adauga link catre document cu test cases executate si incarcate pe github. Test cases results vor fi exportate din Jira.***

### 3.7 Bugs report
 - The bugs reported could be found here: ***vom adauga link catre document cu defectele raportate in Jira pt test case-urile failed**

### 3.8 Test completion report
 - link to test completion report (Test cases ran, how many TC are passed and how many are failed)
   ***vom adauga screenshot cu test completion report din Jira la sfarsitul testarii (toate test case-urile au fost executate)***

### 3.9 Schedule
 - we have 10 days of testing
 - we have 30 functional and GUI tests
 - in order to finish the regression run we would need to run an ~ of 3 tests/day
