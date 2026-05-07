This project focuses on:

* Re-Architecture

Redesigning portions of the application architecture to better align with cloud-native services and scalability patterns.

* Re-Factor

Modernizing components of the application and infrastructure to leverage managed AWS services while reducing operational overhead.


AWS Services Used
* AWS Elastic Beanstalk
* Amazon RDS (MySQL)
* Amazon ElastiCache (Memcached)
* Amazon MQ (RabbitMQ)
* Application Load Balancer (ALB)
* Amazon Route53
* AWS Certificate Manager (ACM)
* Amazon S3
* IAM Roles & Policies
* CloudWatch Monitoring
* 
🧠 Cloud Migration Strategy

 Project Objectives


* Reduce infrastructure management overhead


* Improve scalability and high availability


* Migrate backend services to managed AWS offerings


* Improve deployment consistency and reliability


* Modernize application architecture using cloud-native services



🏗️ Architecture Improvements
Before Modernization


* Manually managed EC2 infrastructure


* Self-hosted database and messaging services


* High operational overhead


* Limited scalability



After Modernization


* Managed application hosting with Elastic Beanstalk


* Managed database using Amazon RDS


* Managed caching using ElastiCache


* Managed messaging using Amazon MQ


* Improved scalability and fault tolerance


* Simplified operational management



⚙️ Application Components
Frontend Layer


* Route53 DNS routing


* HTTPS via ACM


* Application Load Balancer



Application Layer


* Java application deployed to Elastic Beanstalk


* Apache Tomcat platform


* Auto scaling and health monitoring handled by AWS



Backend Layer
* Amazon RDS
* Managed relational database service hosting MySQL database
* Amazon ElastiCache
* Managed Memcached cluster for application caching
* Amazon MQ
* Managed RabbitMQ service for messaging and asynchronous communication

🔁 Deployment Workflow


* Build Java application using Maven


* Package application artifact (.war)


* Upload application version to Elastic Beanstalk


* Deploy application environment


* Configure Route53 DNS


* Enable HTTPS using ACM


* Validate health and connectivity



📁 Project Structure
.├── src/                    # Application source code├── pom.xml                 # Maven build configuration├── README.md               # Project documentation├── Jenkinsfile             # CI/CD pipeline└── .ebextensions/          # Elastic Beanstalk configuration

🛠️ Prerequisites


AWS Account


AWS CLI configured


Java 17+


Maven


Git



🌐 Access the Application
After deployment:
https://vprobean.tcapp.xyz/

🔐 Security Features


HTTPS enabled using AWS Certificate Manager


Security Groups restricting backend access


Managed IAM permissions


Load balancer health monitoring


Private backend service communication



📊 Monitoring & Reliability


Elastic Beanstalk health monitoring


CloudWatch metrics and logs


Load balancer health checks


Auto scaling support


Managed backend service failover



⚠️ Common Issues
Application Not Loading


Verify Elastic Beanstalk environment health


Check Tomcat logs


Validate WAR deployment



Database Connectivity Issues


Verify RDS security groups


Confirm database endpoint configuration



Load Balancer Health Check Failures


Validate health check path


Ensure application is listening on correct port



🔮 Future Improvements


Containerize application using Docker


Deploy to Amazon ECS or EKS


Add CI/CD automation with Jenkins/GitHub Actions


Implement Terraform Infrastructure as Code


Add centralized logging and monitoring


Blue/Green deployment strategy



🎯 Skills Demonstrated


AWS Cloud Architecture


Application Modernization


Re-Architecture & Re-Factor Migration Strategies


Elastic Beanstalk Deployment


AWS Managed Services


Load Balancing & DNS


Java Application Deployment


Cloud Networking & Security


DevOps & Automation



📚 Key Takeaways
This project demonstrates how traditional applications can be modernized using AWS managed services to achieve:


Reduced operational overhead


Increased scalability


Improved reliability


Simplified deployments


Cloud-native modernization



🙌 Author
Tina Collins

⭐ Portfolio Value
This project showcases hands-on experience with:


Cloud migration strategies


AWS PaaS/SaaS services


Application modernization


Enterprise cloud architecture


Real-world DevOps workflows


