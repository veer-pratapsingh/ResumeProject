# ResumeProject
Resources
Azure for students
Azure Static Web apps extension
Visual Studio Code
 
Creating your resume
Writing a resume is an important activity in landing your first job as a student. It's also important later in life for those times you're looking to grow in your career.

 
Azure Static Web apps
Azure Static Web Apps is an Azure service that lets you deploy simpler static sites as well as web apps built in a SPA framework. It even lets you add an API to build a fullstack app.

In short, there's a great grow up story.

 
Tools for deployment and app lifecycle
Azure Static Web apps let's you deploy using more than one way, you can use of any of the following approaches:

Azure CLI.
Azure Static Web apps extension
Azure Portal.
Azure Static Web Apps CLI.
 
How it works
Azure Static Web apps does more for you than just deployment. In fact it handles the complete app dev lifecycle. The first time you deploy, it creates a CI/CD pipeline so that any future changes, you only need to focus on pushing commits to GitHub. The rest, to redeploy, is all taken care of by a .yml file created in a .github directory in you repo. High-level, here's what's going on:

 

Deploy the first time

Project deployed.
.yml file created in repo creating a CI/CD pipeline.
GitHub actions deploying everything using the .yml file above.
 

Future changes

You push commits to your repo
Everything is built and deployed using GH actions and your .yml file.
 
Deploy your resume
To deploy our resume, we need the following software installed.

 
Prerequisites
To deploy our resume, we need the following:

A GitHub account and we need to be logged in.
Visual Studio Code installed.
Azure Static Web Apps and VS Code extension installed.
 
Deployment
In this deployment, you can definitely create your own resume and repo or create one from this template. ( you need to be logged in to GitHub before you attempt to click template link or it will respond with 404)

If you start with static files (not from a GH repo), you will get some questions below regarding Git.

Type (Command + P or Control P) to open the command palette.
Type "Azure Static Web Apps: Create Static Web App" to start the deployment process.
Select your subscription
Select "Create" when asked to create a Git repo as well as GH repo (if you start with only static files, if you start from a repo, you won't get this question)
Enter a commit message, you can select what it proposes, i.e "Initial commit"
Enter name of static web app
Enter name of GH repository (it will be created for you)
Select a region
Select "Custom" as preset
Enter location of application /
Enter location of build output, clear this field.
From here, it should be deploying your project - Congrats, your resume is online

 
Summary
You learned how you can deploy your resume in minutes using Azure Static Web Apps and Visual Studio Code.
