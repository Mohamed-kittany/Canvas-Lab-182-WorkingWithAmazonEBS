# Working with Amazon EBS

## Lab Overview

Amazon Elastic Block Store (Amazon EBS) is a scalable, high-performance block-storage service designed for Amazon Elastic Compute Cloud (Amazon EC2). In this lab, you will learn how to create an EBS volume and perform operations such as attaching it to an instance, creating a file system, and taking a snapshot backup.

## Diagram

<img width="813" alt="lab-scenario" src="https://github.com/Mohamed-kittany/Canvas-Lab-182-WorkingWithAmazonEBS/assets/161580792/5ec324e1-2543-48b0-8252-5f285b2ecdf4">


The diagram shows an EC2 instance with an attached EBS volume and a snapshot created from the EBS volume.

## Objectives

- Create an EBS volume.
- Attach and mount an EBS volume to an EC2 instance.
- Create a snapshot of an EBS volume.
- Create an EBS volume from a snapshot.

## Tasks

1. **Creating an EBS Volume**: 
   - Navigate to the EBS section of the AWS Management Console.
   - Create a new EBS volume with the desired size and type.
   
2. **Attaching and Mounting the EBS Volume to an EC2 Instance**:
   - Attach the created EBS volume to an existing EC2 instance.
   - Connect to the EC2 instance using SSH.
   - Create a file system on the EBS volume.
   - Mount the EBS volume to a directory on the EC2 instance.

3. **Creating a Snapshot of the EBS Volume**:
   - Navigate to the Snapshots section in the EBS console.
   - Create a snapshot of the attached EBS volume to back up the data.

4. **Creating an EBS Volume from a Snapshot**:
   - Use the created snapshot to create a new EBS volume.
   - Attach and mount the new EBS volume to an EC2 instance to verify the data integrity.

