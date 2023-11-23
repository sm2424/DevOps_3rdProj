DevOps_3rdProj=> Git-Docker-Ansible-Jenkins
![Screenshot (160)](https://github.com/sm2424/DevOps_3rdProj/assets/91906122/39aff51f-493b-46ed-9eca-53e1d0aa41a3)# 

**SSH on ec2**

=>add in hosts
vim /etc/hosts

**=>vim /etc/ssh/sshd_config**

permitrootlogin yes

PasswordAuthentication yes

PubkeyAuthentication yes


**=>systemctl restart sshd**


=> other server must have password for root user
passwd root

ssh-keygen

ssh-copy-id -i root@serverA private ip

ssh-copy-id -i root@serverB private ip










