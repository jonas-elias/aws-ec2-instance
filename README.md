# Create a instance AWS EC2

#### Create your account in AWS

<img src='./images/create_account.png'>

#### Access panel EC2
https://sa-east-1.console.aws.amazon.com/ec2

#### Execute instance

<img src='./images/execute_instance.png'>

#### Configuration for the instance

Choose ubuntu server for your application

<img src='./images/ubuntu_instance.png' style="margin-bottom: 30px;">

Create key for putty

<img src='./images/access_putty.png'
style="margin-bottom: 20px;">

Execute/Create instance

<img src='./images/create_instance.png'>

#### Download Putty - Access to instance

<img src='./images/putty_download.png'>

#### Access to instance

Get to key auth to instance

<img src='./images/key_in_putty.png'
style="margin-bottom: 20px;">

Entry to instance with your public IP

<img src='./images/connect_ip_aws_ec2.png'
style="margin-bottom: 20px;">

Login in ubuntu:

```bash
ubuntu
```

#### Update dependencies

```bash
sudo apt-get update
sudo apt-get upgrade
```

#### Install apache
    
```bash
sudo apt-get install apache2
```

#### Enable ports in AWS EC2 Manager

<img src='./images/group_security_1.png'
style="margin-bottom: 20px;">
<img src='./images/group_security_2.png'
style="margin-bottom: 20px;">
<img src='./images/group_security_3.png'>

<!-- #### Installing UFW -->

## Contributing
...
## License
[MIT](https://choosealicense.com/licenses/mit/)