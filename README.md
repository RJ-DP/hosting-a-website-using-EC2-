
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
![Screenshot 2025-11-01 123413.png](https://github.com/user-attachments/assets/12eca7bc-75f6-48f0-9c13-3a264a1cd585)


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
### Check in browser → http://yourpublicip

* An Apache page will be shown to your public ip.
```
cd /var/www/html
sudo rm index.html
sudo vi index.html
```
* Press I to insert your own html code.
* Write your own code.
* After writing all code , Press Ctrl+C and then write ":wq" and Press Enter.


