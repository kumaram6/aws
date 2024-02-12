# Create EC2 Instance

1. **Sign in to the AWS Management Console**: Go to [AWS Management Console](http://awslogin.intel.com/) and sign in using your AWS account credentials.

2. **Navigate to EC2 Dashboard**: Once logged in, navigate to the EC2 dashboard by searching for EC2 under services.

3. **Launch Instance**: Click on the "Launch Instance" button to initiate the process of creating a new EC2 instance.

4. **Choose an Amazon Machine Image (AMI)**: Select an AMI that matches your requirements. An AMI is a template containing the software configuration necessary to launch your instance.

5. **Choose an Instance Type**: Select an instance type based on your workload requirements, defining the virtual hardware such as CPU, memory, storage, and networking capacity.

6. **Generate Key Pair**: For logging into your instance, create a .pem file with RSA.

7. **Configure Instance Details**: Configure instance settings like the number of instances, network settings (VPC, subnet, IP addressing), IAM role, monitoring, and other advanced options.

8. **Add Storage**: Specify the size and type of storage (EBS volumes) to attach to your instance. Additional volumes can be added if required.

9. **Add Tags (Optional)**: Organize and identify resources by adding tags. Tags are key-value pairs that can be assigned to AWS resources.

10. **Configure Security Group**: Define the security group for your instance, acting as a virtual firewall controlling traffic to and from your instance. You can set inbound and outbound rules to allow or restrict specific types of traffic.

11. **Review Instance Launch**: Review all configurations made for your instance. Ensure everything is correct before proceeding.

12. **Launch Instance**: Once satisfied with the configurations, click the "Launch" button. You'll be prompted to select an existing key pair or create a new one for secure access to your instance.

13. **Access Your Instance**: After launching your instance, connect to it using SSH (for Linux instances) or RDP (for Windows instances) using the private key or password associated with your instance.
