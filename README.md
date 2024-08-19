# The Complete OpenTofu Workshopw

## Agenda

### Introduction to OpenTofu (30 minutes)

1. Welcome and Overview
    * Brief introduction of the workshop agenda and goals.
    * Introduce myself and your background with OpenTofu.
2. What is OpenTofu?
    * Overview of OpenTofu as an open-source Infrastructure as Code tool.
    * Key features and benefits of using OpenTofu.
3. Core Concepts
    * Explanation of key concepts: providers, resources, and modules.
    * High-level architecture of OpenTofu.


### Getting Started with OpenTofu (45 minutes)

1. Installing OpenTofu
    * Guide participants through the installation process.
2. Basic Configuration
    * Basic setup: providers, backend configuration.
    * Writing a simple configuration to manage local file resources or a random provider.
    * Hands-on exercise to familiarize participants with HCL (HashiCorp Configuration Language).
3. Applying and Verifying Configuration
    * Steps to apply the configuration.
    * Verifying the results and troubleshooting common issues.
4. Outputs
    * Examine outputs
    * Using remote state to pass values between separate modules
5. The State File
    * What is the state file for?
    * When / how to manipulate it.
    * Where to store it.
    * Encrypting state


### Code Organization and Workspaces (45 minutes)

1. Organizing Code in OpenTofu
    * Best practices for structuring your OpenTofu configuration files and git repos.
    * Using modules to encapsulate and reuse code.
    * Example: Bringing in a module to manage a common resource.
2. Introduction to Workspaces
    * Overview of OpenTofu workspaces and their importance for managing environments.
    * How workspaces help maintain parity across different stages (development, staging, production).
3. Implementing Workspaces
    * Step-by-step guide on creating and switching between workspaces.
    * Example use case: setting up separate workspaces for different environments.
4. Managing State and Dependencies
    * How to manage state files across different workspaces.
    * Handling dependencies and shared resources between workspaces.
5. Setting up OpenTofu for team usage
    * Using TACOs: Terraform Automation and COllaboration
    * Using Policy-as-Code tools like Opa and Checkov


### Building a New EC2 Instance with a Simple Web App (1 hour)

1. Creating a New EC2 Instance
    * Step-by-step guide on writing the configuration for an EC2 instance.
    * Discuss key attributes and configuration options for EC2 in OpenTofu.
2. Deploying a Simple Web App
    * Brief introduction to the web app (no need to go in-depth as the focus is on OpenTofu).
    * Explain how to use user data scripts to install and start the web app on the EC2 instance.
3. Verifying the Deployment
    * Show how to verify that the EC2 instance is running and the web app is accessible.


### Importing an Existing RDS Database (45 minutes)

1. Introduction to RDS in OpenTofu
    * Brief overview of AWS RDS and its integration with OpenTofu.
2. Importing an Existing RDS Database
    * Guide participants through the process of importing an existing RDS instance into OpenTofu.
    * Discuss the necessary configuration and considerations for importing resources.
3. Connecting the Web App to the RDS Database
    * Modify the web app configuration to connect to the imported RDS database.
    * Discuss environment variables and secrets management for database credentials.
4. Testing the Connection
    * Verify that the web app can successfully connect to and interact with the RDS database.
    * Troubleshooting common issues.


### Q&A and Wrap-up (15 minutes)

1. Q&A Session
    * Open the floor for participants to ask questions about the workshop content or any other OpenTofu-related topics.
2. Wrap-up
    * Recap the key points covered in the workshop.
    * Provide resources for further learning (documentation, community forums, etc.).
    * Thank participants for attending and share any upcoming events or workshops related to OpenTofu.
