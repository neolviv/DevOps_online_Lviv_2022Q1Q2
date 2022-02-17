## TASK 2.2

### 1. Reviewed all terms of using AWS Free Tier
### 2. Signed up for Amazon Web Services.

![img](images/aws_reg.jpg)

### 3. Found the hands-on toturials and AWS Well-Architected labs and explored list of step-by-step tutorials
### 4. Reviewed Getting started with Amazon EC2.
-According to results of AWS cloud ping test(https://cloudpingtest.com/aws)
Most suitable region for my ISP is Europe (Frankfurt) | eu-central-1
![img](images/awslatency.jpg)

-Changing region to Europe (Frankfurt) | eu-central-1
![img](images/ec2_1.jpg)

-Created instance with Amazon Linux 2(CentOS) operating system
![img](images/ec2_2.jpg)

-choosing instance type
![img](images/ec2_3.jpg)

-configuring instance details(1 instance)
![img](images/ec2_4.jpg)

-configuring storage
![img](images/ec2_5.jpg)

-adding Name tag
![img](images/ec2_6.jpg)

-creating new Security Group for SSH connection with defined source ip of my home router
![img](images/ec2_7.jpg)

-reviewing instance before launching
![img](images/ec2_8.jpg)

-creating a new key pair and downloading into file
![img](images/ec2_9.jpg)

-checking running instances
![img](images/ec2_10.jpg)

-connected to instance using mobaXterm application, configuring client
![img](images/ec2_11.jpg)\

-working on ssh shell
![img](images/ec2_12.jpg)

### 5. Creating a snapshot of instance to keep as backup, select instance>Actions>Image and Templates>Create template from instance
![img](images/ec2_13.jpg)
![img](images/ec2_14.jpg)

### 6. Creating and attach a Disk_D(EBS) to instance to add more storage spave
![img](images/ec2_15.jpg)
![img](images/ec2_16.jpg)

-attaching volume to instance #1
![img](images/ec2_17.jpg)

-creating and storing some files on Disk_D
![img](images/ec2_18.jpg)
![img](images/ec2_19.jpg)

### 7. Launching the second instance from backup(from Instances menu choosing Launch Templates)
![img](images/ec2_20.jpg)
![img](images/ec2_21.jpg)

### 8. Detaching Disk_D from 1st instance and attaching Disk_D to new instance
![img](images/ec2_22.jpg)

-Connecting to instance #2 and mount EBS Disk_D
![img](images/ec2_23.jpg)

### 9. Reviewed an example of creating own domain
-crating own domain andrewz.pp.ua
![img](images/nicua1.jpg)
![img](images/nicua2.jpg)

-done
![img](images/nicua3.jpg)

### 10. Launching and configuring a WordPress instance with Amazon Lightsail
-creating instance
![img](images/ls1.jpg)

-creating ssh key pair and choosing instance plan
![img](images/ls2.jpg)

-identifing instance
![img](images/ls3.jpg)

-instance created
![img](images/ls4.jpg)

-connecting to instance command line and viewing password to WordPress managment interface
![img](images/ls5.jpg)

-connecting to WordPress web managment interface
![img](images/ls6.jpg)

-getting static ip for instance
![img](images/ls6.jpg)

-attaching our instance static ip address to pp.ua nameserver
![img](images/nicua3.jpg)

-accessing WordPress website directly by ip
![img](images/ls11.jpg)

### 11. Reviewed the tour on S3 Service
-creating own S3 repository
![img](images/s3_1.jpg)

-repository "andrews-1-bucket" created
![img](images/s3_2.jpg)

-uploading "IP_MASK.JPG" file to "andrews-1-bucket" repository
![img](images/s3_3.jpg)

-file successfuly uploaded
![img](images/s3_4.jpg)

-trying to download file to local folder
![img](images/s3_5.jpg)

-deleting files from bucket
![img](images/s3_6.jpg)

-successfuly deleted
![img](images/s3_7.jpg)

### 12. Reviewed the example on using the AWS CLI with Amazon S3
-creating a user with AWS IAM
![img](images/s3_8.jpg)
![img](images/s3_9.jpg)
![img](images/s3_10.jpg)

-user created
![img](images/s3_11.jpg)

-configure AWS CLI and upload any files to S3
![img](images/s3_12.jpg)
![img](images/s3_13.jpg)

### 13. Reviewed the example on deploying Docker Containers on Amazon Elastic Container Service (Amazon  ECS)  
-configuring instance, installing updates and docker
![img](images/ecs1.jpg)
![img](images/ecs2.jpg)

-creating Dockerfile and adding code inside, building Docker image and verifing image was created correctly
![img](images/ecs3.jpg)

-runnning docker image
![img](images/ecs4.jpg)

-trying to connect to instance from external by ip adreess to ensure Docker running and hosting container
![img](images/ecs5.jpg)

-creating an Amazon ECR repository to store image
![img](images/ecs6.jpg)

-taging the hello-world image and running the aws ecr get-login-password command
![img](images/ecs7.jpg)

-Push the image to Amazon ECR
![img](images/ecs8.jpg)

-private repositories on AWS ECS managment console
![img](images/ecs9.jpg)

### 14. Runing a Serverless "Hello, World!" with AWS Lambda
-entering AWS Lambda managment interface
![img](images/ld1.jpg)

-creating function in AWS Lambda managment interface
![img](images/ld2.jpg)

-configuring blueprint
![img](images/ld3.jpg)

-function created
![img](images/ld4.jpg)

-configuring test event
![img](images/ld5.jpg)

-running function and reviewing execution result
![img](images/ld6.jpg)

-viewing CloudWatch metrics of used resources
![img](images/ld7.jpg)


### 15. Creating a static website on Amazon S3
-creating new bucket andrewz.pp.ua
![img](images/s3s_1.jpg)

-configuring static wrbsite hosting for created bucket
![img](images/s3s_2.jpg)

-got bucket website endpoint address
![img](images/s3s_3.jpg)

-configuring polices of the bucket
![img](images/s3s_4.jpg)

-uploaded index.html and me.jpg(my photo according to the task)
![img](images/s3s_5.jpg)

-configuring domain ns server
![img](images/nicua5.jpg)

-result of visiting http://www.andrewz.pp.ua/ is redirection to static website on Amazon S3
![img](images/s3s_6.jpg)
