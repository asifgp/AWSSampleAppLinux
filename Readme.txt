

Add these to user data:

sudo yum -y update
sudo yum -y install ruby
sudo yum -y install wget
cd /home/ec2-user

#For installing CodeDeploy agent on EC2
wget https://aws-codedeploy-ap-south-1.s3.ap-south-1.amazonaws.com/latest/install
sudo chmod +x ./install
sudo ./install auto


#Installing python, pip and awscli
sudo yum install -y python-pip
sudo pip install awscli


