# INSTALL TERRAFROM ON UBUNTU 

- REFERENCE LINK: 

```bash
https://computingforgeeks.com/how-to-install-terraform-on-ubuntu/?expand_article=1
```

- First, install repository addition dependencies:

```bash
sudo apt update
sudo apt install  software-properties-common gnupg2 curl
```

- Now import repository GPG key:

```bash
curl https://apt.releases.hashicorp.com/gpg | gpg --dearmor > hashicorp.gpg
sudo install -o root -g root -m 644 
```

- With the key imported now add Hashicorp repository to your Ubuntu system:

```bash
sudo apt-add-repository "deb [arch=$(dpkg --print-architecture)] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
```

- Now install terraform on your Ubuntu Linux system:

```bash
sudo apt install terraform
```

- Check the version of terraform installed on your system:

```bash
terraform --version
```