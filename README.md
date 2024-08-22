# Building a Serverless Application with AWS Lambda

 - **NAME:** SIBISIDDHARTH G
 - **COMPANY:** CODTECH IT SOLUTIONS
 - **INTERN ID:** CT08DS5286  
 - **DOMAIN:** CLOUD COMPUTING 
 - **BATCH DURATION:** 23 JULY to 23 AUGUST 2024  
 - **MENTOR:** MUZAMMIL AHMED

### Overview of the project:
This project involves deploying a serverless web application using AWS Lambda and API Gateway. The application code is written in Python, tested, and then deployed. API Gateway is configured to trigger the Lambda function, making the web application accessible via a URL.
### Project:DEPLOYING A WEB APPLICATION ON AWS

### Objectives:
The objective of the project is  to deploy a simple web application using Amazon Web Services (AWS). This project will teach the basics of cloud deployment, including setting up a server and configuring the web application.

### Key activities:
 Creating a EC2 Instance
 Importing a sample web application

 ### Technologies used:
 Amazon Web Services Cloud: Created a instance in Amazon web services.
 Linux: Using the Linux commands the web application is deployed in server.

 ### **Writing and Deploying the Lambda Function Code**

1. **Write the Code:**
   - In the function’s code editor, write your Lambda function code in Python. The code should handle HTTP requests and return appropriate responses.
 
2. **Deploy the Code:**
   - Click "Deploy" to save and deploy your code.
   - This makes the function live and ready to be invoked.
  
## Detailed Procedure:

### Updating the System:

Ensure that your Amazon Linux 2 instance is running the latest software and security updates. This step prepares the environment for installing new software.

### Installing the Apache HTTP Server:

Install Apache HTTP Server (httpd) to handle HTTP requests and serve your web application to users.

### Verifying the Apache Installation:

Check the status of the Apache service to confirm that it is installed correctly. The service might be inactive initially, but it will be addressed in subsequent steps.

### Preparing the Web Application Files:

Download or clone the web application files from a repository or ZIP archive. These files include `index.html`, `styles.css`, `script.js`, and image files.

### Deploying the Web Application:

Move the web application files to the `/var/www/html/` directory. This directory is used by Apache HTTP Server to serve web content.

### Configuring and Starting the Apache HTTP Server:

Enable Apache HTTP Server to start on boot and start the service. This ensures that the server is running and serving your web application.

### Verifying the Deployment:

Access the public IP address of your EC2 instance in a web browser to confirm that the web application is being served correctly.

The application is now accessible via the public IP address of your EC2 instance, demonstrating a successful deployment on AWS.

## Linux Commands Used:

### Switching to the root user:

sudo su -

### Updating the system:

yum update -y

### Installing the Apache HTTP Server:

yum install -y httpd

### Checking the status of the Apache HTTP Server:

systemctl status httpd

### Creating a directory named 'tech':

mkdir tech

### Navigating to the tech directory:

cd tech

### Downloading the GitHub repository:

wget https://github.com/codewithsadee/anon-ecommerce-website

 ### Launching an EC2 Instance:

 

