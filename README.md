![Alt text](Host_LAMP_Stack_Website.png)

**Project:** Hosting a LAMP Stack Website on AWS

**Project Overview:** In this project, I set up a LAMP Stack (Linux, Apache, MySQL, PHP) Stack Website on Amazon Web Services (AWS) utilizing various AWS services to ensure Scalability, High availability, and security. Below is a summary of the key components and steps involved in the deployment:

**Deployment Steps:**

1. **Virtual Private Cloud (VPC):**
   - Configured a VPC with public and private subnets across two availability zones for enhanced reliability and fault tolerance.

2. **Internet Gateway:**
   - An Internet Gateway was deployed to facilitate VPC instances and Internet connectivity.

3. **Security Groups:**
   - Established Security Groups as a network firewall mechanism to control traffic to EC2 instances.

4. **Availability Zones:**
   - Leveraged 2 Availability Zones to enhance system reliability and fault tolerance.

5. **Public Subnets:** 
   - Utilized Public Subnets for infrastructure components like the NAT Gateway and Application Load Balancer.

6. **Utilized Bastion Host:**
   - Implemented Bastion Host for secure connection to assets within both public and private subnets.

7. **Web Servers (EC2 Instances):**
   - Provisioned web servers within Private Subnets for enhanced security.

8. **NAT Gateway:**
   - Enabled instances in private Applications and Data subnets to access the Internet via the NAT Gateway.

9. **Auto Scaling Group:**
   - Employed an Auto Scaling Group to automatically manage EC2 instances, ensuring website high availability, scalability, fault tolerance, and elasticity.

10. **GitHub for Version Control:**
    - Stored web files on GitHub for version control and collaboration.

11. **Application Load Balancer (ALB):**
    - Utilized an Application Load Balancer and a target group for evenly distributing web traffic to the Auto Scaling Group of EC2 instances across multiple Availability Zones.

12. **Certificate Manager:**
    - Secured application communication using a Certificate Manager.

13. **Simple Notification Service (SNS):**
    - Configured SNS to alert about activities within the Auto Scaling Group.

14. **Route 53:**
    - Registered the domain name and set up a DNS record using Route 53.

15. **Amazon S3** 
    - Created an S3 Bucket to store web content.

16. **PHP**
    - Installed PHP for dynamic and interactive websites. 

17. **Flyway:**
    - Utilized Flyway to import data into the RDS MySQL database.

**Repository:** The project reference diagram and deployment steps are available in the GitHub repository. Please take a look at the repository for detailed instructions on deploying the LAMP Stack website on AWS infrastructure.

**Conclusion:** By following the instructions and utilizing the provided resources, you can successfully deploy a LAMP Stack web application on AWS, ensuring high availability, security, and scalability.
