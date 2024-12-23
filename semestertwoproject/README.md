# Provisioning a Linux Server with a Simple Landing Page

## Project Overview

This project demonstrates the process of provisioning a Linux server on AWS,
setting up a web server, and deploying a simple HTML landing page to showcase
my skills and capabilities. The page includes a brief description about me,
as well as a bio and project details. The goal is to give potential investors
and collaborators a clear view of what I can do.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Project Details](#project-details)
- [Live Demo](#live-demo)
- [License](#license)
- [Contact Information](#contact-information)

## Technologies Used

- Linux Server: Ubuntu 20.04 LTS
- Web Server: Apache HTTP Server
- HTML: Simple static webpage
- Cloud Service: AWS (Amazon Web Services)

## Setup Instructions

### Step 1: Provision the Server
1. Log into AWS Console and launch an EC2 instance.
2. Choose an Ubuntu 20.04 LTS AMI.
3. Select an instance type (t2.micro for free tier).
4. Configure network settings and security groups to allow HTTP traffic on port 80.
      Add an Inbound Rule for HTTP:
      Type: HTTP
      Protocol: TCP
      Port Range: 80
      Source: Anywhere (0.0.0.0/0) for global access 

5. Connect to instance using EC2 Instance Connect

### Step 2:
1. Install apache web server
   sudo apt update
   	sudo apt install apache2 -y

2. Start the web server
   sudo systemctl start apache2
   	sudo systemctl enable apache2

### Step 3:
1. Navigate to the web server directory /var/www/html
2. create index.html file and write code

### Step 4:
1. Restart web browser

### Step 5:
1. Allow HTTP traffic is allowed by confirming port 80 is open
2. Access the webpage at http://18.175.236.63/

## Project Details
This project is intended to demonstrate my ability to set up a Linux server and
deploy a static webpage on a cloud infrastructure. The page includes a brief
introduction, project description, and a bio with interesting facts about me.
This serves as a landing page for investors and collaborators to learn more about
my skills and background.

Key Features
1. Linux-based server deployment.
2. Simple, responsive HTML landing page.
3. Configured and hosted on AWS EC2 with Apache.


## Live Demo
You can view the live demo of the project at:

Live Demo URL: http://18.175.236.63/

## License
This project is open-source and available under the MIT License.

Contact Information
For any questions, collaboration inquiries, or further details, feel free to contact me:

Email: damilola.afolayan007@gmail.com
GitHub: github.com/Mcdharmie
LinkedIn: linkedin.com/in/mcdharmie
