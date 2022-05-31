### DAST(OWASP ZAP) Scan with Gitlab CI

Step 1: Register/Login to gitlab

Step 2: Create a gitlab project

Step 3: Click on Import Project Image

![0.png](0.png)


Step 4: Select Repo by URL from the list of options and fill 
https://github.com/Security-Champions-Beta/Gitlab_CI-DAST-OWASP_ZAP.git
as the Git repository URL and specify a project name. Once done, click the Create Project button Image

    https://github.com/Security-Champions-Beta/Gitlab_CI-DAST-OWASP_ZAP.git

![1.png](1.png)

![7.png](7.png)

Step 5: Click on README.md file and Edit it by adding some text. Once done, click on Commit changes Image

![8.png](8.png)


Step 6: Navigate to Pipelines under CI/CD on the sidebar. Now click on the pipeline, and you will a job that has been created due to our recent commit. Wait for the job to complete.

Step 7: Once the scan is complete, click on the menu option to download the artifacts Image


![9.png](9.png)


![88.png](88.png)

Step 8 : Read OwaspZap report

![888.png](888.png)

Step 9 : Verify on Docker

![8888.png](8888.png)