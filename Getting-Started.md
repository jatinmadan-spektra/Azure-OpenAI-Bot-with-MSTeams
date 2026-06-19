# Empower Knowledge Workers using Azure OpenAI with MS Teams and Azure Bot Service

### Overall Estimated Duration: 3 hours

## Overview

Contoso leverages **Azure OpenAI** to build a sophisticated AI assistant integrated with **Microsoft Teams** and **Azure Bot Service**. This setup allows employees to interact with the assistant for context-aware support, automating routine tasks, retrieving company knowledge, and receiving intelligent recommendations. The integration enhances productivity, streamlines workflows, and improves decision-making by embedding advanced AI capabilities directly within their communication platform.

In this hands-on lab, you will earn how to use the Azure OpenAI service to create an AI powered solution with the latest AI technologies.

## Objective

Learn to leverage an OpenAI model to extract data and create embeddings, deploy it with Flask locally and on Azure App Service, and integrate the chatbot with Azure Bot Service and Azure Logic Apps for end-to-end automation and communication.

- **Leveraging an OpenAI model to create extract data and create embeddings:** Use an OpenAI model to extract data and create embeddings for advanced data processing and retrieval. Participants will learn to extract data and create embeddings using an OpenAI model for advanced data analysis.

- **Deploying the model using Flask framework locally and on Azure App Service:** Deploy the model locally with Flask and on Azure App Service for scalable web access. Participants will achieve the deployment of the OpenAI model both locally with Flask and on Azure App Service for scalable web-based access.

- **Deploying the chatbot on Azure Bot Service and Azure App Service and Setting up Email Automation Workflow on Azure Logic:** Deploy the chatbot on Azure Bot Service and Azure App Service, and set up an email automation workflow using Azure Logic Apps for seamless communication. Participants will successfully deploy a chatbot on Azure Bot Service and Azure App Service, and set up an email automation workflow using Azure Logic Apps for integrated communication and automation.

## Prerequisites

Participants should have:

- **Understanding of AI and Machine Learning:** Basic knowledge of data extraction and embeddings with OpenAI models.
- **Proficiency in Python and Flask:** Experience in building and deploying web applications using Flask.
- **Familiarity with Azure Services:** Knowledge of Azure App Service, Azure Bot Service, and Azure Logic Apps.
- **Web Development Skills:** Experience in developing and managing web-based applications.
- **Cloud Deployment Skills:** Basic understanding of deploying applications on cloud platforms like Azure.

## Architecture

The architecture involves using **Azure OpenAI Service** to provide advanced AI capabilities for data extraction and embedding creation. A **Flask** application serves as the interface to deploy this model locally and on **Azure App Service**, which hosts the web application and manages scalability. The **Azure Bot Service** is used to deploy and manage the chatbot, integrating it with various communication channels. Finally, **Azure Logic Apps** automates workflows such as email notifications, enabling seamless communication and process automation triggered by interactions with the chatbot or other events within the system.

## Architecture Diagram

![](Images/diagram.png)

## Explanation of Components

The architecture for this lab involves the following key components:

- **Azure OpenAI Service:** Provides access to OpenAI models for tasks such as data extraction and creating embeddings. This service enables you to leverage advanced AI capabilities for processing and analyzing data.
- **Flask Framework:** A lightweight Python web framework used to build and deploy the OpenAI model locally. It also facilitates the deployment of the model on Azure App Service by creating a web application that interfaces with the AI model.
- **Azure App Service:** A fully managed platform for building, deploying, and scaling web apps. You'll use Azure App Service to host the Flask application and deploy the OpenAI model in a scalable and secure environment.
- **Azure Bot Service:** Enables you to deploy, manage, and integrate the chatbot into various channels, including Microsoft Teams and web applications. This service provides tools for creating and maintaining conversational AI solutions.
- **Azure Logic Apps:** Facilitates the creation of automated workflows, including email automation. You’ll use Logic Apps to set up workflows that automate email notifications and other processes triggered by events or data changes.

## Getting Started with the Lab Environment

## Accessing Your Lab Environment

Once you're ready to begin, your virtual machine and lab guide will be available directly within your web browser.

![](./Images/change-7.png)

## Virtual Machine & Lab Guide

The virtual machine provides access to the Azure Portal and Microsoft security portals.  
The lab guide remains visible throughout the lab exercises.

## Exploring Your Lab Resources

Navigate to the **Environment** tab to review lab resources and credentials.

![](./Images/change-2.png)

## Utilizing the Split Window Feature

Use the **Split Window** button in the top-right corner to open the lab guide in a separate window for easier navigation.

![](./Images/change-3.png)

## Managing Your Virtual Machine

Start, stop, or restart your virtual machine as needed from the **Resources** tab.

![](./Images/change-4.png)

## Lab Guide Zoom In / Zoom Out

Adjust the zoom level using the **A↕ : 100%** icon located next to the timer.

![](./Images/zoominout1.png)

## Let's Get Started with Azure Portal

1. On the virtual machine, click the **Azure Portal** icon:

    ![](./Images/vm101.png)

1. On the **Sign in to Microsoft Azure** page, enter:

   - **Email/Username:** <inject key="AzureAdUserEmail" enableCopy="true"/>

       ![](./Images/sign1.png)

1. Enter the Temporary Access Pass, and click Sign in:

   - **Temporary Access Pass:** <inject key="AzureAdUserPassword" enableCopy="true"/>

      ![](./Images/tpwrd.png)

1. Select **No** when prompted to stay signed in.

   ![](./Images/sign001.png)

## Support Contact

CloudLabs support is available 24/7 to assist learners and instructors.

- **Email:** cloudlabs-support@spektrasystems.com  
- **Live Chat:** https://cloudlabs.ai/labs-support  

Now, click on **Next** from the lower right corner to move on to the next page. 

![](./Images/next.png)

### Happy Learning!!