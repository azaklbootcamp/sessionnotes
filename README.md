# Azure Bootcamp 2018 Session Notes and Lab Walkthrough

This session is designed to help understand some of the basics of deploying Azure Resources with the use of tools such as Visual Studio or Visual Studio Code and a Git repository such as Visual Studio Team Services or Github. During the course of this session, we would be looking at deploying the various tiers of Azure resources which would form the base for a highly redundant Azure Web Site hosted on Azure App Service. 

**Aben Samuel**

_Principal Consultant,Fusion5_

[Website](http://wellytonian.com) | [@neop26](https://twitter.com/neop26)

**What do you need?**
1. An Azure Subscription
2. A install of either Visual Studio Community or Visual Studio (Why not provision a VM on Azure that has Visual Studio?)
3. Or you can use Visual Studio Code as well
4. Have fun building it out!

**GITHUB Repo**

https://github.com/azaklbootcamp

**Web App URLS**

`bootcampwebappsydney.azurewebsites.net`

`bootcampwebappmelb.azurewebsites.net`

**Lab Walkthrough**
1. Create a free Github account 
2. Clone the following two repositories to your Github Account
	https://github.com/azaklbootcamp/Bootcampwebapp
	https://github.com/azaklbootcamp/SingleAppGW
3. Connect Visual Studio to your Github Account
4. Clone your respository - Bootcampwebapp (From Visual Studio)
5. Make a branch and then make some code edits
6. Publish the Web Application from VS
7. Setup Continous Deployment - Integrating Github to your Azure Tenant.
8. Make some changes and update the code and check in the changes.
9. Merge the branch so that you can see deployment onto Azure starts immediately.
10. View the changes.
11. Close the solution.

**Building a Single Application Gateway ( From Visual Studio Code)**
1. Clone your repository - SingleAppGW
2. Make a branch and then make some code edits
3. Deploy the App Gateway Code to deploy a single Application Gateway pointed at both the Web Apps

**Building our Highly Redundant Platform ( From Visual Studio Code)**
1. Clone your repository - RedundantPlatform

