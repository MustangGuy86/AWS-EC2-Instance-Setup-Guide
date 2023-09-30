# AWS-EC2-Instance-Setup-Guide
This guide will walk you through setting up and accessing an Amazon EC2 instance, a virtual server in the AWS cloud. It's suitable for beginners with no prior AWS experience.
# AWS EC2 Instance Setup Guide

This guide will walk you through setting up and accessing an Amazon EC2 instance, a virtual server in the AWS cloud. It's suitable for beginners with no prior AWS experience.

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Step 1: Log in to Your AWS Account](#step-1-log-in-to-your-aws-account)
4. [Step 2: Access the EC2 Dashboard](#step-2-access-the-ec2-dashboard)
5. [Step 3: Launch an EC2 Instance](#step-3-launch-an-ec2-instance)
6. [Step 4: Choose an Amazon Machine Image (AMI)](#step-4-choose-an-amazon-machine-image-ami)
7. [Step 5: Configure Instance Details](#step-5-configure-instance-details)
8. [Step 6: Add Storage](#step-6-add-storage)
9. [Step 7: Add Tags (Optional)](#step-7-add-tags-optional)
10. [Step 8: Configure Security Group](#step-8-configure-security-group)
11. [Step 9: Review and Launch](#step-9-review-and-launch)
12. [Step 10: Select Key Pair](#step-10-select-key-pair)
13. [Step 11: Launch Status](#step-11-launch-status)
14. [Step 12: Access Your EC2 Instance](#step-12-access-your-ec2-instance)

## Prerequisites
- An AWS account: [Sign Up for AWS](https://aws.amazon.com/)
- Basic knowledge of using an SSH client (e.g., PuTTY on Windows, Terminal on macOS/Linux)

## Step 1: Log in to Your AWS Account
1. Open your web browser and go to the [AWS Console](https://aws.amazon.com/console/).
2. Click on "Sign In to the Console."
3. Enter your AWS account credentials (email address and password), then click "Sign In."

## Step 2: Access the EC2 Dashboard
4. After successfully logging in, you will be on the AWS Management Console. In the top navigation bar, you will see "Services." Click on it.
5. In the "Compute" section, locate and click on "EC2" (Elastic Compute Cloud). This will take you to the EC2 Dashboard.

## Step 3: Launch an EC2 Instance
6. In the EC2 Dashboard, on the left sidebar, under "Instances," click on "Instances."
7. Click the "Launch Instance" button to start the process of creating a new EC2 instance.

## Step 4: Choose an Amazon Machine Image (AMI)
8. In the "Choose an Amazon Machine Image (AMI)" step, you'll be presented with a list of available AMIs. These are pre-configured virtual machine templates.
9. Select an AMI that suits your needs. For beginners, you can use the default "Amazon Linux 2 AMI" as a starting point.
10. Click "Next: Configure Instance Details" to proceed.

(Continue with the remaining steps in the same format as above.)

## Step 12: Access Your EC2 Instance
28. In the EC2 Dashboard, under "Instances," you will see your running instance.
29. To access the instance, you can use an SSH client (e.g., PuTTY on Windows or the terminal on macOS/Linux) with the private key you downloaded earlier.

Congratulations! You've successfully created your first Amazon EC2 instance. You can now access and manage it as needed.

For more information and advanced configurations, please refer to the AWS documentation.

**Note:** Always be mindful of AWS costs when running instances. Remember to stop or terminate instances when not in use to avoid unexpected charges.

For troubleshooting and additional help, please visit the [AWS Support Center](https://aws.amazon.com/premiumsupport/).

Feel free to fork this repository and customize this README for your specific setup. Enjoy your AWS journey!
