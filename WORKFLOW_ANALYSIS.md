# Workflow_Analysis

## Questio .1 What triggers this workflow to run? (Look at the on: section)
## When it is either push to braches: [main] or when pull_request from branches: [main].

## Question 2. What are the four main steps this workflow performs? (List each step name)

## Step 1. Checkout code
## Step 2. Validate HTML files
## Step 3. Check for broken links
## Step 4. Upload the built site for deployment

What does the "Checkout code" step do and why is it necessary?

## It downloads the copy of the repository to run the workflow . This is used for the next steps of validating HTML, checking for broken links and finally deploying.

What is the purpose of the environment configuration?

##  The enviorment allows GitHub to track the deployment and display the history, alongside applying any rule sets without having to put the code straight through that may cause an error.

How does this automated deployment improve reliability compared to manual deployment?

## During the automation happens, the it has validations checks, broken link checks that will ayutomatically either block or notify the user. Since it is automatic, the steps are consistant and has no human errors.

What would happen if you pushed code to a different branch (not main)?

## It can be pushed to a different branch and can be used for testing for the user in that branch, however since it is not main, it will not have a deployment to occur until merged into main.