# AWS Auto Scaling Demo 🚀

This project demonstrates how to deploy a simple web application on AWS using **Auto Scaling**, **Launch Templates**, and an **Application Load Balancer (ALB)**.

---

## 🧩 Project Overview

This setup automatically scales EC2 instances based on traffic load.  
When traffic increases, new instances launch automatically, and when load decreases, unnecessary instances terminate.

---

## 🛠️ AWS Components Used

- **Target Group (TG):** Routes traffic to healthy EC2 instances.  
- **Application Load Balancer (ALB):** Distributes incoming traffic.  
- **Launch Template:** Defines the EC2 configuration and user data script.  
- **Auto Scaling Group (ASG):** Automatically adjusts the number of instances.  
- **Security Group:** Allows HTTP (port 80) inbound traffic.

---

## 🧾 User Data Script

```bash
#!/bin/bash
yum install httpd -y
service httpd start
chkconfig httpd on
mkdir /var/www/html
echo 'Welcome ! Website with auto scaling by Parminderjit' > /var/www/html/index.html



# Auto-Scaling-on-AWS-Cloud
perform Auto scaling

<img width="1233" height="642" alt="image" src="https://github.com/user-attachments/assets/316c77ce-a1f6-47ce-8a45-7b8bfda2f5d7" />


#!/bin/bash
yum install httpd -y
service httpd start
chkconfig httpd on
mkdir /var/www/hrml
echo 'Welcome ! Website with auto scaling by Parminderjit ' > /var/www/html/index.html


<img width="1081" height="644" alt="image" src="https://github.com/user-attachments/assets/e6798868-8308-432f-8971-663a6d30549d" />




<img width="1231" height="656" alt="image" src="https://github.com/user-attachments/assets/cceb1481-d7b3-4c98-a9d7-9e997949ae72" />





<img width="1260" height="577" alt="image" src="https://github.com/user-attachments/assets/387ea9aa-c905-4254-98bf-50f3f30fea86" />


<img width="1229" height="640" alt="image" src="https://github.com/user-attachments/assets/cb50d6de-a3a3-49cb-9a35-05793fc56cf1" />



<img width="1264" height="593" alt="image" src="https://github.com/user-attachments/assets/69a46956-bd9e-434d-b2e2-afdb3f615be3" />




# AWS Auto Scaling Demo 🚀

This project demonstrates how to deploy a simple web application on AWS using **Auto Scaling**, **Launch Templates**, and an **Application Load Balancer (ALB)**.

---

## 🧩 Project Overview

This setup automatically scales EC2 instances based on traffic load.  
When traffic increases, new instances launch automatically, and when load decreases, unnecessary instances terminate.

---

## 🛠️ AWS Components Used

- **Target Group (TG):** Routes traffic to healthy EC2 instances.  
- **Application Load Balancer (ALB):** Distributes incoming traffic.  
- **Launch Template:** Defines the EC2 configuration and user data script.  
- **Auto Scaling Group (ASG):** Automatically adjusts the number of instances.  
- **Security Group:** Allows HTTP (port 80) inbound traffic.

---

## 🧾 User Data Script

```bash
#!/bin/bash
yum install httpd -y
service httpd start
chkconfig httpd on
mkdir /var/www/html
echo 'Welcome ! Website with auto scaling by Parminderjit' > /var/www/html/index.html


