# Packer Installation 

## Login as a root user in ec2 instance
```
sudo su -
```

## You will need to upgrade your system and packages
```
yum update -y
```

## Install wget and unzip packages
```
yum install wget unzip vim -y
```

## Go to /opt dir
```
cd /opt
```

## Download the Vault software.
https://www.vaultproject.io/downloads/

wget https://releases.hashicorp.com/vault/1.3.2/vault_1.3.2_linux_amd64.zip

## Extract the terraform software.
```
unzip vault_1.3.2_linux_amd64.zip -d /usr/local/bin/
```

## Check the version
```
vault -v (OR) vault --version
```

## Help
```
vault  -help
```
