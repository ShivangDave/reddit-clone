#!/bin/bash

yum update -y
yum install -y httpd
yum install git -y
systemctl start httpd
systemctl enable httpd
git clone https://github.com/ShivangDave/reddit-clone.git
cd reddit-clone
cp -a . /var/www/html/.
