# AWS-EC2-Launch-Instance
Read on [Medium Link](https://medium.com/@ejadaji7/aws-ec2-launch-instance-cf6e709a58bc?source=user_profile_page---------1-------------a93f2578e95f----------------------)

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

<img width="1100" height="664" alt="image" src="https://github.com/user-attachments/assets/793ce063-4a8f-430c-9f45-577c182ceeb3" />


<img width="1100" height="694" alt="image" src="https://github.com/user-attachments/assets/ba482e92-5ab2-4b51-9cd6-e7bdbad3d448" />


4. I entered a descriptive name for Name of the instance from the Name and tags.

5. Using Amazon linux I chose my first linux instance as operating system(OS). And selected a free tier eligible Amazon Machine Image()AMI.

<img width="1100" height="694" alt="image" src="https://github.com/user-attachments/assets/4366507c-07dd-4548-9b6d-ef9e54d63499" />


6. Chose t2.micro instance type which is available for instance type in my region.

<img width="1100" height="705" alt="image" src="https://github.com/user-attachments/assets/57618d66-7d53-4e55-a3a5-9d60768a817c" />


8. I proceeded without creating a key pair.

<img width="1100" height="697" alt="image" src="https://github.com/user-attachments/assets/9a1591a7-486f-4686-83d4-89e40d8d7498" />


9. Selected a default VPC using the default subnet in an availability zone that was chosen and configured a security group with roles that would allow connections to the instance from anywhere .

<img width="1100" height="412" alt="image" src="https://github.com/user-attachments/assets/0a6b340e-2251-42d5-b2bd-8f3a4eaf16a9" />


10. A root volume was configured under configure storage.

11. Checked the summary of the instance from the summary panel and launched instance.

<img width="1100" height="456" alt="image" src="https://github.com/user-attachments/assets/ce725008-debf-4956-9550-e19c0450a18a" />


<img width="1372" height="547" alt="image" src="https://github.com/user-attachments/assets/30fb785e-8dd8-4e33-b336-8a9fe7ba6787" />


12. The instance was successful and running .

<img width="1382" height="537" alt="image" src="https://github.com/user-attachments/assets/12bdb0c3-fbed-4842-a244-6b35dd305591" />






