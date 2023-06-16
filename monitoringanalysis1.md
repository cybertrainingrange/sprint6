# MONITOR AND ANALYSIS IN AWS

# Summary

**Monitoring and scanning** are essential practices in maintaining the security and health of your AWS environment. AWS provides a comprehensive suite of services that leverages to enhance your monitoring and scanning capabilities within the AWS ecosystem. Several monitoring and analysis tools are available in AWS to help you monitor and gain insights into your infrastructure, applications, and security. Here are some monitoring and analysis tools available in AWS.
- Amazon CloudWatch.
- AWS CloudTrail.
- AWS Config.
- AWS X-Ray.
- AWS Trusted Advisor.
- AWS Personal Health Dashboard.
- Amazon Inspector.
- AWS Security Hub. 
- Amazon VPCFlow Logs.

By combining these cost-effective options, we can establish a basic Monitoring & Analysis setup for our Cyber Training Range in AWS without incurring significant additional expenses. 

## Amazon CloudWatch

**CloudWatch** is a centralized monitoring service that provides monitoring, logging, and alarming for your AWS resources and applications. It collects and tracks metrics, collects log files, sets alarms, and can trigger automated actions based on defined thresholds.
Utilize AWS CloudWatch to monitor your AWS resources and applications. CloudWatch offers metrics, logs, and alarms for monitoring various services and can help you identify performance issues or anomalies. This helps you identify security events, troubleshoot issues, and maintain visibility across your environment.
Amazon CloudWatch collects and visualizes real-time logs, metrics, and event data in automated dashboards to streamline your infrastructure and application maintenance.






|    ![CloudWatch](https://drive.google.com/uc?export=view&id=1-c7vDiqjKJQNWSwnKLsWu09_YBSmoXi_)    |
| ----------------------- |




**Use Cases:**

- Monitor application performance
Visualize performance data, create alarms, and correlate data to understand and resolve the root cause of performance issues in your AWS resources.
- Perform root cause analysis
Analyze metrics, logs, logs analytics, and user requests to speed up debugging and reduce overall mean time to resolution.
- Optimize resources proactively
Automate resource planning and lower costs by setting actions to occur when thresholds are met based on your specifications or machine learning models.
- Test website impacts
Find out exactly when your website is impacted and for how long by viewing screenshots, logs, and web requests at any point in time. 



## AWS CloudTrail

**CloudTrail** is a service that enables you to log, continuously monitor, and retain account activity related to API actions. It provides detailed event history and helps with security analysis, resource change tracking, and compliance auditing.
AWS CloudTrail enables you to log and monitor API activity within your AWS account. CloudTrail provides detailed event history, allowing you to track changes, investigate incidents, and detect unauthorized activity.







![AWS CloudTrail](https://drive.google.com/uc?export=view&id=1K9mrxfdWBX0VayxxJDOfBGT2SBME2nqW)   





AWS CloudTrail enables auditing, security monitoring, and operational troubleshooting. CloudTrail records user activity and API calls across AWS services as events. CloudTrail events help you answer the question of "Who did what, where, and when?". AWS CloudTrail monitors and records account activity across your AWS infrastructure, giving you control over storage, analysis, and remediation actions.

**CloudTrail records two types CloudTrail of events:**

- Management events that capture control plane actions on resources, such as creating or deleting Amazon Simple Storage Service (S3) buckets.
- Data events that capture data plane actions within a resource, such as reading or writing an Amazon S3 object.
 
**CloudTrail can also ingest data through its native integration with other AWS services:**
 
- Configuration items from AWS Config that capture resource configuration history and resource compliance history as evaluated by AWS Config rules.
- Audit evidence from AWS Audit Manager that contains the information needed to demonstrate compliance with the requirements as specified by Audit Manager controls.

## AWS Config

**AWS Config** continually assesses, audits, and evaluates the configurations and relationships of your resources on AWS, on premises, and on other clouds. It continuously monitors and records configuration changes and can provide compliance assessments against desired configurations.
AWS Config enables you to assess and monitor the configuration of your AWS resources over time. AWS Config provides a detailed inventory of your resources, configuration history, and compliance checks to help ensure consistent security and governance.









![AWS Config](https://drive.google.com/uc?export=view&id=1M_Ka6LH9fzlMHrwZ_OS8zuKdpdqDivZc)





## AWS X-Ray:

**AWS X-Ray** provides a complete view of requests as they travel through your application and filters visual data across payloads, functions, traces, services, APIs, and more with no-code and low-code motions. X-Ray is a distributed tracing system that helps you understand how your applications are performing and where issues may arise. It provides insights into requests as they flow across different services, helping you analyze and debug complex architectures.







![AWS X-Ray](https://drive.google.com/uc?export=view&id=1GfhJKrCT0puZrU4iuEHy4s7N1jHvwlz0) 





## AWS Personal Health Dashboard

**The Personal Health Dashboard** provides alerts and notifications about the health of your AWS resources. It proactively notifies you of any planned maintenance, service disruptions, or security vulnerabilities that may impact your environment. You can view the overall status of AWS services, and you can sign in to view personalized communications about your particular AWS account or organization. Your account view provides deeper visibility into resource issues, upcoming changes, and important notifications.

**Benefits**

- Personalized view of service health
  
- Proactive notifications
  
- Detailed troubleshooting guidance
  
- Integration and automation
  
- Fine-grained access control by using IAM
  
- Aggregate health events across AWS Organizations


## AWS Trusted Advisor

**Trusted Advisor** is a service that provides real-time guidance to help optimize your AWS environment. It offers checks and recommendations in areas such as cost optimization, performance, security, and fault tolerance. It offers recommendations based on AWS best practices.

   **Benefits:**

Checks from Trusted Advisor analyze your AWS environment and recommend actions to follow best practices.

- Cost optimization
  
Trusted Advisor can help you save cost with actionable recommendations by analyzing usage, configuration and spend. Examples include identifying idle RDS DB instances, underutilized EBS volumes, unassociated Elastic IP addresses, and excessive timeouts in Lambda functions.

- Performance

Trusted Advisor can help improve the performance of your services with actionable recommendations by analyzing usage and configuration. Examples include analyzing EBS throughput and latency, compute usage of EC2 instances, and configurations on CloudFront.

- Security
  
Trusted Advisor can help improve the security of your AWS environment by suggesting foundational security best practices curated by security experts. Examples include identifying RDS security group access risk, exposed access keys, and unnecessary S3 bucket permissions.

- Fault tolerance
  
Trusted Advisor can help improve the reliability of your services. Examples include examining Auto scaling EC2 groups, deleted health checks on Route 53, disabled Availability Zones, and disabled RDS backups.

- Service quotas

Service quotas are the maximum number of resources that you can create in an AWS account. AWS implements quotas to provide highly available and reliable service to all customers, and protects you from unintentional spend.


## Amazon Inspector

**Amazon Inspector** is an automated security assessment service that helps you identify security vulnerabilities and deviations from security best practices. It performs security assessments on EC2 instances, identifying common security issues and providing prioritized recommendations. Amazon Inspector is an automated vulnerability management service that continually scans AWS workloads for software vulnerabilities and unintended network exposure. Amazon Inspector automatically discovers workloads, such as Amazon EC2 instances, containers, and Lambda functions, and scans them for software vulnerabilities and unintended network exposure.






| ![Amazon Inspector](https://drive.google.com/uc?export=view&id=1ANdGy5Hik5PX37U3qpaVyoBh-TH92kpE)    |
| ----------------------- |



**Use cases:**

- Quickly discover zero-day vulnerabilities in compute workloads
  
- Prioritize patch remediation
  
- Meet compliance requirements


## AWS Security Hub:

**Security Hub** is a comprehensive security service that aggregates and prioritizes security alerts from various AWS services, as well as third-party tools. It provides a central dashboard for security findings, automated compliance checks, and integrations with other security services. Use AWS Security Hub to automate security best practice checks, aggregate security alerts into a single place and format, and understand your overall security posture across all of your AWS accounts.





| ![Amazon Inspector](https://drive.google.com/uc?export=view&id=1t6gWfpAcc6PFAT3JloiFpRw9YmOxwNHv)  |
| ----------------------- |




AWS Security Hub enables you to aggregate and prioritize security alerts from various AWS services and third-party tools. It provides a consolidated view of your security posture, automated compliance checks, and integrates with other security tools.



## Amazon VPC Flow Logs

VPC Flow Logs capture information about the IP traffic going to and from network interfaces in your Amazon VPC. They can be used for network monitoring, troubleshooting, and analyzing network traffic patterns and anomalies. Amazon VPC Flow Logs capture information about the IP traffic going to and from network interfaces in your Amazon VPC. Analyzing flow logs can help you detect and investigate network anomalies or unauthorized access attempts.


**Reference**


- https://aws.amazon.com/cloudwatch/
- https://aws.amazon.com/config/
- https://aws.amazon.com/cloudtrail/
- https://aws.amazon.com/xray/?nc2=type_a
- https://aws.amazon.com/premiumsupport/technology/aws-health-dashboard/
- https://aws.amazon.com/premiumsupport/technology/trusted-advisor/
- https://aws.amazon.com/inspector/?nc2=type_a
- https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html
- https://youtu.be/K7V5kNBjGCI
- https://www.youtube.com/watch?v=eIUZdaqColg&list=PLhr1KZpdzukdbisTs-Eskg4xsfLFOki1T&index=12


## Technical Documentation 🤖

[Creating AWS CloudWatch Alarm](https://docs.google.com/document/d/1G6xxnjuSboOvlquU-TPcgbBXRw4WvkIXXchY0V2Jsog/edit?usp=share_link)




## 🔗 Authors: 👐



### Ameha Zewde Lemma 👨
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ameha-lemma/)
- [@Ameha Zewde Lemma](https://github.com/orgs/cybertrainingrange/people/ameha01)

### Alena👩‍
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alena-puzach-b999801a7/)
- [@Alena](https://github.com/alenapuzach)
  
### Vohla👩‍
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/Vohla/)
- [@Vohla](https://github.com/voliatalatynik)
  
