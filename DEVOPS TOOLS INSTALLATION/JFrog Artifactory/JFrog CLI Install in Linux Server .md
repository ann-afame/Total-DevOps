# JFrog CLI in Linux Server
## Login as a root user
```
sudo su -

echo "[jfrog-cli]" > jfrog-cli.repo;
echo "name=jfrog-cli" >> jfrog-cli.repo;
echo "baseurl=https://releases.jfrog.io/artifactory/jfrog-rpms" >> jfrog-cli.repo;
echo "enabled=1" >> jfrog-cli.repo; echo "gpgcheck=0" >> jfrog-cli.repo;
sudo mv jfrog-cli.repo /etc/yum.repos.d/;
yum install -y jfrog-cli-v2;
```

JFrog CLI Installation in MAC
----------------------------------------
```
brew install jfrog-cli
```
## To check the Version use the below command
```
jfrog -v
```

Reference URL

--------------------

https://jfrog.com/getcli/
