**Load Test Exercise with JMeter**
Each commit or pull request triggers the load test in GitHub Actions. To see the pipeline in action, push a new commit and go to Actions tab to see the Workflow running.
Html results in zipped format are attached as artifact to the completed workflow. It can be downloaded and the report can be seen in the browser. 

**Script Execution**
To execute the script locally follow the steps below:
1. Clone the repo
2. Download JMeter
3. Open terminal and go to the bin folder of JMeter
4. Run the folowing command to generate an HTML report of the execution:
jmeter -n -t "path to the jmx file" -l "path to the output.csv" -e -o "path to the new Html Results folder"
Note: The folder that would contain the output.csv and the HTML Results folder should be empty.

**Scenarios**
Following scenarios are covered:
1.	Perform a load test of 1000 visitors visiting the web app’s home page in a 15 seconds period.
2.	Perform an end-to-end performance test of a checkout workflow.
3.	Define a way to pass parametrized login credentials for logging into an application with 10 different users.
4.	Define the pacing required for the application load test for the below specifications: 
Total number of iterations in one hour - 15000
Total Number of users - 1000
Total flows – Search flow 50%, Place order - 35 % and Replace order - 15%

AUT: https://www.demoblaze.com and http://www.automationpractice.com

**Included in the repo:**
1. Execution Results: Execution_Results.zip
2. Test Report: TestReportFinal.pdf
