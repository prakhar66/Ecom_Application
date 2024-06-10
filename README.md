Objective:
The goal of this assignment is to perform performance testing on Ecommerce application to evaluate its scalability, reliability, and performance under different loads.

Load Testing: Simulate concurrent users to assess the application's performance.

Instructions to Run Performance Tests
Choose a Performance Testing Tool:
We are taken LoadRunner as it supports various web based applications and give comprehensive test results.

Create Test Scenarios:
Load Testing Scenario: Define the number of concurrent users and the duration. Here we have 3 modules to test with 40 user load.

Set Up Test Environment:
Ensure the application is running.
Configure the performance testing tool to target http://localhost:8080.

Running Performance Tests with Microfocus LoadRunner

Install LoadRunner:

Download and install LoadRunner from the Micro Focus website.
Follow the installation instructions provided by Micro Focus.

Create a New LoadRunner Script:
Open LoadRunner and create a new Virtual User (Vuser) script.
Choose the appropriate protocol for your application. For this project we use HTTP/HTML.

Record a Test Script:
Start recording a new script by navigating to Record -> Record Script.
Perform typical user actions on the application (e.g., User creation, Promotion Active, Campaign Creation & Edit).
Stop recording and save the script.

Enhance the Script:
Add parameterization to your script to simulate different user inputs.
Insert checkpoints to verify server responses.
Correlate dynamic values that change with each session.

Configure Runtime Settings:
Adjust runtime settings such as pacing, think time, and iterations to simulate real-world usage.

Create a Load Test Scenario:
Open the Controller component of LoadRunner.
Create a new scenario and add your recorded script to the scenario.
Define the number of virtual users and the duration of the test.
Set up load generators to distribute the load across multiple machines if necessary.

Run the Load Test:
Start the load test from the Controller.
Monitored the test execution in real-time using LoadRunner’s monitoring tools.

Analyze Results:
After the test completes, open the Analysis component of LoadRunner.
Analyze key performance metrics such as response time, throughput, and error rates.
Generated detailed reports in attached Excel to identify performance bottlenecks.


By following these steps, we are able to effectively set up and execute performance tests on this Ecom web application.
