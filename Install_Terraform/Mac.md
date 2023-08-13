# INSTALLATION TERRAFORM ON MAC

- REFERENCE LINK: 

```bash
https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli
```

- Install Homebrew on mac terminal    

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- Install the HashiCorp tap, a repository of all our Homebrew packages     

```bash
brew tap hashicorp/tap
```

- Install Terraform with hashicorp/tap/terraform

```bash
brew install hashicorp/tap/terraform
```

- To update to the latest version of Terraform, first update Homebrew

```bash
brew update
```

- Run the upgrade command to download and use the latest Terraform version

```bash
brew upgrade hashicorp/tap/terraform
```
