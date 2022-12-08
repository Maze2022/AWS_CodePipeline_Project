# AWS_CodePipeline_Project

Your team has asked you to create a way to automate the deployment of a website. Currently your developers have to go through the process manually to test each new update to their code. You'll need to provide the static site URL to the developers and also make a modification to the code in the GitHub repo to verify the pipeline is working.

1.	Create a new repository in GitHub or CodeCommit and load the attached HTML.
2.	Create and configure a S3 bucket to host your static website.
3.	Create a CI/CD pipeline using the AWS Codepipeline service .
4.	Set your repo as the Source Stage of the Codepipeline that is triggered when an update is made to a GitHub repo.
5.	For the deploy stage select your S3 bucket.
6.	Deploy the pipeline and verify that you can reach the static website.
7.	Make an update to the code in your github to verify that the codepipeline is triggered. This can be as simple as a change to the Readme file because any change to the files should trigger the workflow.
