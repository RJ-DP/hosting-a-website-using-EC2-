
# Hosting a Website on AWS EC2 
## Steps to Deploy
### 1. Launch EC2 Instance
* Go to AWS Console, then EC2, then Launch Instance
* Choose Ubuntu
* Create and Use key pair
* Use Putty
* Allow HTTP (80), HTTPS (443), and SSH (22)
* Launch instance

## Launched EC2 Instance
![](https://github.com/user-attachments/assets/3bee775a-f9a6-47b4-ae7d-c35ca5d699da />)
### 2. Connect to EC2 (using PuTTY/SSH)
* Download Putty.exe file and install it in your device.
* Go to connection.
* Go to SSH
* Go to Auth
* Choose key pair file you made while creating instance.
```
login as username: ubuntu
```
### 3. Install Apache
```
sudo apt install apache2
```



