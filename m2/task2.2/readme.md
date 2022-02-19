## TASK 2.2

### 1. Reviewed all terms of using AWS Free Tier
### 2. Signed up for Amazon Web Services.

<details>
  <summary>Click to expand!</summary>
  
  ![img](images/aws_reg.jpg)
</details>

### 3. Found the hands-on toturials and AWS Well-Architected labs and explored list of step-by-step tutorials
### 4. Reviewed Getting started with Amazon EC2.
-According to results of AWS cloud ping test (https://cloudpingtest.com/aws)
Most suitable region for my ISP is Europe (Frankfurt) | eu-central-1
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/awslatency.jpg)
</details>


-Changing region to Europe (Frankfurt) | eu-central-1
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_1.jpg)
</details>


-Created instance with Amazon Linux 2(CentOS) operating system
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_2.jpg)
</details>


-choosing instance type
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_3.jpg)
</details>


-configuring instance details(1 instance)
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_4.jpg)
</details>


-configuring storage
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_5.jpg)
</details>


-adding Name tag
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_6.jpg)
</details>


-creating new Security Group for SSH connection with defined source ip of my home router
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_7.jpg)
</details>


-reviewing instance before launching
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_8.jpg)
</details>


-creating a new key pair and downloading into file
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_9.jpg)
</details>


-checking running instances
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_10.jpg)
</details>


-connected to instance using mobaXterm application, configuring client
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_11.jpg)
</details>


-working on ssh shell
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_12.jpg)
</details>


### 5. Creating a snapshot of instance to keep as backup, select instance>Actions>Image and Templates>Create template from instance
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_13.jpg)
  ![img](images/ec2_14.jpg)
</details>


### 6. Creating and attach a Disk_D(EBS) to instance to add more storage spave
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_15.jpg)
  ![img](images/ec2_16.jpg)
</details>


-attaching volume to instance #1
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_17.jpg)
</details>


-creating and storing some files on Disk_D
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_18.jpg)
  ![img](images/ec2_19.jpg)
</details>


### 7. Launching the second instance from backup(from Instances menu choosing Launch Templates)
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_20.jpg)
  ![img](images/ec2_21.jpg)
</details>


### 8. Detaching Disk_D from 1st instance and attaching Disk_D to new instance
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_22.jpg)
</details>


-Connecting to instance #2 and mount EBS Disk_D
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ec2_23.jpg)
</details>


### 9. Reviewed an example of creating own domain
-crating own domain andrewz.pp.ua
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/nicua1.jpg)
  ![img](images/nicua2.jpg)
</details>

-done
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/nicua3.jpg)
</details>


### 10. Launching and configuring a WordPress instance with Amazon Lightsail
-creating instance
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ls1.jpg)
</details>


-creating ssh key pair and choosing instance plan
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ls2.jpg)
</details>


-identifing instance
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ls3.jpg)
</details>


-instance created
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ls4.jpg)
</details>


-connecting to instance command line and viewing password to WordPress managment interface
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ls5.jpg)
</details>


-connecting to WordPress web managment interface
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ls6.jpg)
</details>


-getting static ip for instance
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ls7.jpg)
</details>


-attaching our instance static ip address to pp.ua nameserver
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/nicua4.jpg)
</details>


-accessing WordPress website directly by ip
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ls11.jpg)
</details>


### 11. Reviewed the tour on S3 Service
-creating own S3 repository
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3_1.jpg)
</details>


-repository "andrews-1-bucket" created
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3_2.jpg)
</details>


-uploading "IP_MASK.JPG" file to "andrews-1-bucket" repository
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3_3.jpg)
</details>


-file successfuly uploaded
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3_4.jpg)
</details>


-trying to download file to local folder
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3_5.jpg)
</details>


-deleting files from bucket
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3_6.jpg)
</details>


-successfuly deleted
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3_7.jpg)
</details>

### 12. Reviewed the example on using the AWS CLI with Amazon S3
-creating a user with AWS IAM
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3_8.jpg)
  ![img](images/s3_9.jpg)
  ![img](images/s3_10.jpg)
</details>


-user created
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3_11.jpg)
</details>


-configure AWS CLI and upload any files to S3
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3_12.jpg)
  ![img](images/s3_13.jpg)
</details>


### 13. Reviewed the example on deploying Docker Containers on Amazon Elastic Container Service (Amazon  ECS)  
-configuring instance, installing updates and docker
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ecs1.jpg)
  ![img](images/ecs2.jpg)
</details>


-creating Dockerfile and adding code inside, building Docker image and verifing image was created correctly
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ecs3.jpg)
</details>


-runnning docker image
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ecs4.jpg)
</details>


-trying to connect to instance from external by ip adreess to ensure Docker running and hosting container
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ecs5.jpg)
</details>


-creating an Amazon ECR repository to store image
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ecs6.jpg)
</details>


-taging the hello-world image and running the aws ecr get-login-password command
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ecs7.jpg)
</details>


-Push the image to Amazon ECR
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ecs8.jpg)
</details>


-private repositories on AWS ECS managment console
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ecs9.jpg)
</details>


### 14. Runing a Serverless "Hello, World!" with AWS Lambda
-entering AWS Lambda managment interface
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ld1.jpg)
</details>


-creating function in AWS Lambda managment interface
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ld2.jpg)
</details>


-configuring blueprint
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ld3.jpg)
</details>


-function created
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ld4.jpg)
</details>


-configuring test event
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ld5.jpg)
</details>


-running function and reviewing execution result
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ld6.jpg)
</details>


-viewing CloudWatch metrics of used resources
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/ld7.jpg)
</details>


### 15. Creating a static website on Amazon S3
-creating new bucket andrewz.pp.ua
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3s_1.jpg)
</details>


-configuring static wrbsite hosting for created bucket
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3s_2.jpg)
</details>


-got bucket website endpoint address
<details>
  <summary>Click to expand!</summary>
  
 ![img](images/s3s_3.jpg)
</details>


-configuring polices of the bucket
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3s_4.jpg)
</details>


-uploaded index.html and me.jpg(my photo according to the task)
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3s_5.jpg)
</details>


-configuring domain ns server
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/nicua5.jpg)
</details>


-result of visiting http://www.andrewz.pp.ua/ is redirection to static website on Amazon S3
<details>
  <summary>Click to expand!</summary>
  
  ![img](images/s3s_6.jpg)
</details>
