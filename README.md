Cloud Security Configuration with AWS and Kali Linux

Project Overview

This project was a hands-on cloud security exercise focused on identifying and reviewing security configurations within an AWS environment.

I used Kali Linux together with AWS security and assessment tools to examine areas such as identity and access management, cloud configuration, exposed services, and potential security weaknesses.

The purpose of the project was to gain practical experience with securing and assessing cloud infrastructure rather than only learning the concepts theoretically.

Objectives

The main objectives of the project were to:

* Configure and interact with AWS resources securely.
* Work with AWS Identity and Access Management (IAM).
* Review cloud security configurations.
* Identify potential security weaknesses and misconfigurations.
* Use security assessment tools to evaluate the AWS environment.
* Practice cloud security assessment from a Kali Linux environment.
* Document findings and security recommendations.

Environment

Cloud Platform

* Amazon Web Services (AWS)

Operating System

* Kali Linux
* Kali Linux running through VirtualBox

Tools

* AWS CLI v2
* AWS IAM
* Prowler
* ScoutSuite
* cURL
* VirtualBox

Project Setup

The assessment environment consisted of a Kali Linux virtual machine used to interact with and assess the AWS environment.

AWS CLI was installed and configured on Kali Linux to allow secure command-line interaction with AWS services.

The AWS environment was configured to use the us-north-1 region.

IAM Security

One of the main areas reviewed was AWS Identity and Access Management (IAM).

IAM controls who can access AWS resources and what actions they are permitted to perform.

During the project, I worked with IAM concepts including:

* Users
* Permissions
* Policies
* Access control
* Authentication
* Least-privilege access

The exercise helped demonstrate why permissions should be limited to only what a user or service actually needs.

AWS CLI

AWS CLI was used to interact with the AWS environment from Kali Linux.

This provided practical experience with managing and inspecting cloud resources from the command line rather than relying entirely on the AWS Management Console.

Example activities included checking the configured AWS environment and interacting with AWS services through CLI commands.

Security Assessment with Prowler

Prowler was used to perform automated security checks against the AWS environment.

The tool helped identify areas that required attention based on established AWS security practices.

The assessment provided useful information about areas such as:

* IAM configuration
* Account security
* Logging and monitoring
* Network configuration
* Security best practices

The results were reviewed to understand the potential security implications and identify areas where configurations could be improved.

Cloud Assessment with ScoutSuite

ScoutSuite was also used to assess the AWS environment.

It provided a broader view of the cloud configuration and helped identify potentially risky settings across different AWS services.

Using both Prowler and ScoutSuite provided a practical comparison of cloud security assessment approaches.

Testing with cURL

cURL was used during the project to make HTTP requests and test connectivity to services.

This provided additional hands-on experience with understanding how cloud-hosted services can be accessed and how exposed endpoints should be reviewed from a security perspective.

Security Approach

The project followed several basic cloud security principles:

Least Privilege

Access should be restricted to the minimum permissions required to perform a task.

Identity and Access Management

User access and permissions should be properly controlled to reduce the risk of unauthorized access.

Configuration Review

Cloud resources should be regularly reviewed for insecure or unnecessary configurations.

Security Assessment

Automated tools can help identify security gaps that may otherwise be overlooked during manual reviews.

Continuous Monitoring

Cloud environments should be monitored continuously because configurations, users, permissions, and exposed services can change over time.

What I Learned

This project gave me practical experience with cloud security and helped me understand how AWS environments can be assessed from a security perspective.

I gained hands-on experience with:

* AWS IAM
* AWS CLI
* Cloud security assessment
* Security misconfiguration identification
* Prowler
* ScoutSuite
* Linux security tools
* Cloud access control
* Basic cloud security best practices

It also helped me understand the relationship between identity, permissions, configuration, monitoring, and overall cloud security.

Project Evidence

Screenshots and supporting evidence from the project are included in the images folder.

These include relevant AWS configurations, Kali Linux commands, security assessment results, and testing activities.

Future Improvements

For a more advanced version of this project, I would extend the environment by adding:

* CloudTrail monitoring
* Amazon GuardDuty
* Security Hub
* CloudWatch monitoring
* S3 security configuration
* VPC security controls
* Automated security scanning
* Infrastructure-as-Code security testing

Conclusion

This project provided practical exposure to cloud security using AWS and Kali Linux.

Rather than focusing only on theory, I worked through the process of accessing, reviewing, testing, and assessing a cloud environment using real security tools.

The project strengthened my understanding of AWS security, IAM, cloud configuration, security assessment, and practical cybersecurity troubleshooting.

Author

Oluwadamola Ologan

Cybersecurity | Cloud Security | Network Security

LinkedIn
