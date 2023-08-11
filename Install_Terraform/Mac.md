# INSTALLATION TERRAFORM ON MAC

# 1- REFERENCE LINK: 

```bash
https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli
```

# 2- Install Homebrew on mac terminal    

```bash
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

# 3- Install the HashiCorp tap, a repository of all our Homebrew packages     

```bash
$ brew tap hashicorp/tap
```

# 4- Install Terraform with hashicorp/tap/terraform

```bash
$ brew install hashicorp/tap/terraform
```

# 5- To update to the latest version of Terraform, first update Homebrew

```bash
$ brew update
```

# 6- Run the upgrade command to download and use the latest Terraform version

```bash
$ brew upgrade hashicorp/tap/terraform
```
