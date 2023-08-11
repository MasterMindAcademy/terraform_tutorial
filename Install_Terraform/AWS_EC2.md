# INSTALL TERRAFORM ON AWS EC2 INSTANCE

# 1- Launch an EC2 instance using the Amazon Linux 2 AMI with security group allowing SSH connections.

# 2- Connect to your instance with SSH. Refecence link is given below:

```bash
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/connect-linux-inst-ssh.html
```

# 3- After login to Ec2 instance with SSH connection, Update system

```bash
sudo yum update -y
```

# 4- Install yum-config-manager to manage your repositories.

```bash
sudo yum install -y yum-utils
```

# 5- Use yum-config-manager to add the official HashiCorp Linux repository to the directory of /etc/yum.repos.d.

```bash
sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo
```

# 6- Install Terraform.

```bash
sudo yum -y install terraform
```

# 7- Verify that the installation

```bash
terraform version
```