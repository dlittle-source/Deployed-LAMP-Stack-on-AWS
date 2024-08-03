**Project:** Hosting a LAMP Stack Website on AWS

**Project Overview:** In this project, I set up a LAMP Stack (Linux, Apache, MySQL, PHP) Stack Website on Amazon Web Services (AWS) utilizing various AWS services to ensure Scalability, High availability, and security. Below is a summary of the key components and steps involved in the deployment:

**Deployment Steps:**

**Virtual Private Cloud (VPC):**

1. Configured a VPC with public and private subnets across three availability zones for enhanced reliability and fault tolerance.

2. Deployed an Internet Gateway to facilitate connectivity between VPC instances and the wider Internet.

3. Established Security Groups as a network firewall mechanism to control traffic to EC2 instances.

4. Leveraged 3 Availability Zones to enhance system reliability and fault tolerance.

5. Utilized Public Subnets for infrastructure components like the NAT Gateway and Application Load Balancer.

6. Implemented EC2 Instance Connect Endpoint for secure connection to assets within both public and private subnets.

7. Provisioned web servers within Private Subnets for enhanced security.

8. Enabled instances in both private Application and Data subnets to access the Internet via the NAT Gateway.

9. Employed an Auto Scaling Group to automatically manage EC2 instances, ensuring website high availability, scalability, fault tolerance, and elasticity.

10. Stored web files on GitHub for version control and collaboration.

11. Utilized an Application Load Balancer and a target group for evenly distributing web traffic to the Auto Scaling Group of EC2 instances across multiple Availability Zones.

12. Secured application communication using a Certificate Manager.

13. Configured SNS to alert about activities within the Auto Scaling Group.

14. Registered the domain name and set up a DNS record using Route 53.

15. Created an S3 Bucket to store files.

16. Utilized SQL Workbench to import data into the MySQL database.

**Repository:** The project reference diagram and deployment steps are available in the GitHub repository. Please take a look at the repository for detailed instructions on deploying the LAMP Stack website on AWS infrastructure.

**Conclusion:** By following the instructions and utilizing the provided resources, you can successfully deploy a LAMP Stack web application on AWS, ensuring high availability, security, and scalability.
