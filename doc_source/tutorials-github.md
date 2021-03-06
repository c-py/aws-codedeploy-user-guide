--------

 The procedures in this guide support the new console design\. If you choose to use the older version of the console, you will find many of the concepts and basic procedures in this guide still apply\. To access help in the new console, choose the information icon\. 

--------

# Tutorial: Use AWS CodeDeploy to Deploy an Application from GitHub<a name="tutorials-github"></a>

In this tutorial, you use AWS CodeDeploy to deploy a sample application revision from GitHub to a single Amazon EC2 instance running Amazon Linux, a single Red Hat Enterprise Linux \(RHEL\) instance, or a single Windows Server instance\. For information about GitHub integration with AWS CodeDeploy, see [Integrating AWS CodeDeploy with GitHub](integrations-partners-github.md)\.

**Note**  
You can also use AWS CodeDeploy to deploy an application revision from GitHub to an Ubuntu Server instance\. You can use the sample revision described in [Step 2: Create a Sample Application Revision](tutorials-on-premises-instance.md#tutorials-on-premises-instance-2-create-sample-revision) in [Tutorial: Deploy an Application to an On\-Premises Instance with AWS CodeDeploy \(Windows Server, Ubuntu Server, or Red Hat Enterprise Linux\)](tutorials-on-premises-instance.md), or you can create a revision compatible with an Ubuntu Server instance and AWS CodeDeploy\. To create your own revision, see [Plan a Revision for AWS CodeDeploy](application-revisions-plan.md) and [Add an Application Specification File to a Revision for AWS CodeDeploy](application-revisions-appspec-file.md)\.

**Topics**
+ [Prerequisites](tutorials-github-prerequisites.md)
+ [Step 1: Set Up a GitHub Account](tutorials-github-create-github-account.md)
+ [Step 2: Create a GitHub Repository](tutorials-github-create-github-repository.md)
+ [Step 3: Upload a Sample Application to Your GitHub Repository](tutorials-github-upload-sample-revision.md)
+ [Step 4: Provision an Instance](tutorials-github-provision-instance.md)
+ [Step 5: Create an Application and Deployment Group](tutorials-github-create-application.md)
+ [Step 6: Deploy the Application to the Instance](tutorials-github-deploy-application.md)
+ [Step 7: Monitor and Verify the Deployment](tutorials-github-verify.md)
+ [Step 8: Clean Up](tutorials-github-clean-up.md)