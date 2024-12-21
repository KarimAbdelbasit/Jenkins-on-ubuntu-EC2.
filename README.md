## Jenkins-on-ubuntu-EC2.
Install jenkins in ubuntu and   add inbound rules  custom TCP port 8080
#### Open the websit:
```
https://pkg.jenkins.io/
```
#### Then click on debain and write cmd:
```
  sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
    https://pkg.jenkins.io/debian/jenkins.io-2023.key
```
#### Then add a Jenkins apt repository entry:
```
echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" \
    https://pkg.jenkins.io/debian binary/ | sudo tee \
    /etc/apt/sources.list.d/jenkins.list > /dev/null
```
#### Update your local package index, then finally install Jenkins:
```
sudo apt-get update
```
```
sudo apt-get install fontconfig openjdk-17-jre
```
```
sudo apt-get install jenkins
```



