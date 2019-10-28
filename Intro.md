# Oracle Cloud Infrastructure: Workshop

Updated: October 25th, 2019

Welcome to the **Oracle Public Cloud** OCI workshop. This workshop will walk you through the process of creating a webserver that is able to autoscale if CPU utilization hits a ceratin threshold. This workshop will walk you through the process of creating a compute instace, virtual cloud networking, autoscaling, and the use of Terraform. 

## Introduction

This lab discusses the steps taken to create and setup a compute instance to deploy a web application. Once the web application has been deployed, we will configure an instance pool that will allow our compute instance to autoscale. 

Autoscaling enables you to automatically adjust the number of Compute instances in an instance pool based on performance metrics such as CPU and memory utilization. This helps you provide consistent performance for your end users during periods of high demand, and helps you reduce your costs during periods of low demand.

## Oracle Cloud Account

You will need access to an Oracle Cloud tenancy to complete this workshop.

### **Step 1**: Acquire an Oracle Cloud Trial Account

- Bookmark this page for future reference.

- Click on the URL to create your <a class="trial-link" href="https://myservices.us.oraclecloud.com/mycloud/signup?language=en&sourceType=:ex:tb:::RC_PDMK180212P00140:Docker_HOL&SC=:ex:tb:::RC_PDMK180212P00140:Docker_HOL&pcode=PDMK180212P00140" target="_trial">Free Tier Account</a> and complete all the required steps. When you complete the registration process you'll receive a Free Tier account.  
- The Free Tier account contains services you can use for an unlimited time plus a $300 credit that grants you access to a wide range of Oracle Cloud services for 30 days, including Analytics, Compute, and Container Engine for Kubernetes and much more.
- Follow the link above, enter your **email address** and follow the steps to create your cloud account.  *Please Note:  New email accounts on popular email providers (google, yahoo, etc) created in the last 24 hours will trigger an alert and require you to call support to confirm your account*

  ![](images/cloud-signup.png)

- Soon after requesting your Free Tier account you will receive the following emails.  The first one indicates you have requested an account and provisioning has begun.

  ![](images/signup-email.png)

- The next email you receive will indicate your account is fully setup and ready to go.  Proceed to Step 2.

  ![](images/signup-email-provisioned.png)

### **Step 2**: Navigate to Lab 050

- [Click here to navigate to Lab 050](https://blakeramos.github.io/OCI-Workshop/?version=OCI&page=OCI-050.md)
