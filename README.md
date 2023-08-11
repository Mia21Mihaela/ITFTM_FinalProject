# ITFTM_FinalProject

This is the final project of the itFactory Manual Testing course. The scope of the final project is to utilize all the new developed skills in the corse and practice them on a live application.
---
## Revision History

| Date  | Description  | Author | Comments | 
|---|---|---|---|
| 05.05.2023 | Test Plan for version 0.55 | Mihaela Lisman |   |


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


Application under test: [OpenCart Admin Interface](https://demo.opencart.com/admin) <br>
Application Documentation can be found [here](http://docs.opencart.com/en-gb/introduction/)

### 1.2  Functionalities in scope
The functionalities that are going to be tested are:
* accessing the admin panel with an existing admin account
* entering the administration through the Dashboard
* filer feature
* configurating a new store in the admin panel
* editing a store in the admin panel 

Testing types used: 
* functional testing
* GUI testing
* positive testing
* negative testing
* regression testing
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
| Tester | Mihaela Lisman  | will test: the process of accessing the admin panel and entering the administration through the Dashboard | 
| Tester | Andrei Pop | will test: filter functionality, configurating a new store and editing an existing store in the admin panel |

***Entry criteria***
* functional business specifications are defined
* roles needed for the project are allocated
* testing environment is up and running
* smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing)

***Exit criteria:***
* all test cases have been executed 
* 90% of tests are passed
* no Critical issues/bugs have Open status (All unresolved bugs have low priority and low severity)
* exploratory testing performed on the features: login to the admin panel, logout of the admin panel, dashboard, add new store, edit store, 
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
* entering the administration through the Dashboard
* filer feature
* configurating a new store in the admin panel
* editing a store in the admin panel 

We plan on running a full regression test on the current version of the aplication.

### 2.3 Test design
* All the test cases are written and reviewed 
* Functional test cases will be created in Zephyr Squad using Jira as Test Management tool
* GUI test cases will be created in Zephyr Squad using Jira as Test Management tool
* Positive testing test cases will be created in Zephyr Squad using Jira as Test Management tool
* Negative testing test cases will be created in Zephyr Squad using Jira as Test Management tool
* Regression testing test cases will be created in Zephyr Squad using Jira as Test Management tool
* Cross-browser testing test cases will be created in Zephyr Squad using Jira as Test Management tool

### 2.4 Test implementation
* All the test data is available and reviewed (admin account: username=demo, password=demo; different type of currency: US dollar, euro and pound sterling)
* This test run includes only regression testing in which we will run tests that have the highest priority, this will be main priority
* Cycle summary was created and test cases were added to the cycle summary 
* Test environment is up and running: [OpenCart Admin Interface](https://demo.opencart.com/admin)

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

