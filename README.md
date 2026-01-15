<h1>🚀 AWS Auto Scaling Demo</h1>

<p>
This project demonstrates how to deploy a simple web application on AWS using
<b>Auto Scaling</b>, <b>Launch Templates</b>, and an
<b>Application Load Balancer (ALB)</b>.
</p>

<hr>

<h2>🧩 Project Overview</h2>

<p>
This setup automatically scales EC2 instances based on traffic load.
When traffic increases, new instances launch automatically,
and when load decreases, unnecessary instances terminate.
</p>

<hr>

<h2>🛠️ AWS Components Used</h2>

<ul>
  <li><b>Target Group (TG):</b> Routes traffic to healthy EC2 instances</li>
  <li><b>Application Load Balancer (ALB):</b> Distributes incoming traffic</li>
  <li><b>Launch Template:</b> Defines EC2 configuration and user data</li>
  <li><b>Auto Scaling Group (ASG):</b> Automatically adjusts instance count</li>
  <li><b>Security Group:</b> Allows HTTP (port 80) inbound traffic</li>
</ul>

<hr>

<h2>🧾 User Data Script</h2>

<pre><code>#!/bin/bash
yum install httpd -y
service httpd start
chkconfig httpd on
mkdir -p /var/www/html
echo 'Welcome! Website with Auto Scaling by Parminderjit' &gt; /var/www/html/index.html
</code></pre>

<hr>

<h2>📸 Project Screenshots</h2>

<div class="image-grid">
  <img width="49%" src="https://github.com/user-attachments/assets/316c77ce-a1f6-47ce-8a45-7b8bfda2f5d7" alt="Auto Scaling setup">
  <img width="49%" src="https://github.com/user-attachments/assets/e6798868-8308-432f-8971-663a6d30549d" alt="Launch template">

  <img width="49%" src="https://github.com/user-attachments/assets/cceb1481-d7b3-4c98-a9d7-9e997949ae72" alt="Target group">
  <img width="49%" src="https://github.com/user-attachments/assets/387ea9aa-c905-4254-98bf-50f3f30fea86" alt="Load balancer">

  <img width="49%" src="https://github.com/user-attachments/assets/cb50d6de-a3a3-49cb-9a35-05793fc56cf1" alt="Scaling activity">
  <img  width="49%" src="https://github.com/user-attachments/assets/69a46956-bd9e-434d-b2e2-afdb3f615be3" alt="Healthy instances">
</div>

<hr>

<h2>✅ Outcome</h2>

<ul>
  <li>EC2 instances scale automatically based on load</li>
  <li>ALB distributes traffic across instances</li>
  <li>High availability achieved using ASG</li>
  <li>Hands-on demonstration of AWS Auto Scaling</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
<b>Parminderjit Singh</b><br>
DevOps Fresher | AWS | Auto Scaling | Cloud Infrastructure
</p>

</body>

<hr>
<hr>


