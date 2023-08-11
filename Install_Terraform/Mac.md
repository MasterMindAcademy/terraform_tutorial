# INSTALLATION TERRAFORM ON MAC

# REFERENCE LINK: 

https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli

# Install Homebrew on mac terminal    

$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Install the HashiCorp tap, a repository of all our Homebrew packages     

$ brew tap hashicorp/tap

# Install Terraform with hashicorp/tap/terraform

$ brew install hashicorp/tap/terraform

# To update to the latest version of Terraform, first update Homebrew

$ brew update

# Run the upgrade command to download and use the latest Terraform version

$ brew upgrade hashicorp/tap/terraform