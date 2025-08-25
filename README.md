# AWS-EC2-Launch-Instance
Read on [Medium Link] (https://medium.com/@ejadaji7/aws-ec2-launch-instance-cf6e709a58bc?source=user_profile_page---------1-------------a93f2578e95f----------------------)

In this project, i launched an EC2 instance using the AWS Management console. Using these key components .

An image — a template which has the software that ran on the instance.
A network — a virtual network dedicated to my AWS account which comes with a default Virtual private cloud (VPC) in each AWS Region.
A security group — which controls in and out traffic .
Amongst others .

These are the tasks that we deployed to launch the EC2 instance .

An Amazon EC2 console was opened.
And selected an AWS region near me , North Virginia .
<img width="1400" height="575" alt="image" src="https://github.com/user-attachments/assets/a295de00-3a60-462d-a0e1-2d7f7e0d1703" />


3. From the launch panel on the EC2 dashboard I choose launch instance .

Press enter or click to view image in full size

Press enter or click to view image in full size

4. I entered a descriptive name for Name of the instance from the Name and tags.

5. Using Amazon linux I chose my first linux instance as operating system(OS). And selected a free tier eligible Amazon Machine Image()AMI.

Press enter or click to view image in full size

6. Chose t2.micro instance type which is available for instance type in my region.

Press enter or click to view image in full size

8. I proceeded without creating a key pair.

Press enter or click to view image in full size

9. Selected a default VPC using the default subnet in an availability zone that was chosen and configured a security group with roles that would allow connections to the instance from anywhere .

Press enter or click to view image in full size

10. A root volume was configured under configure storage.

11. Checked the summary of the instance from the summary panel and launched instance.

Press enter or click to view image in full size

Press enter or click to view image in full size

12. The instance was successful and running .

Press enter or click to view image in full size





