# Wordpress-userdata /3 Tier Architecture


fisrtly create vpc and more with 2 public and 4 private subnets without s3 end point and NAT gwatway in two availability zones.

create target group without choose any instace.

create auto launch cofigration or templates and add AMI and add userdata and add dbname'db', dbuser'admin',password'xyx12345',rootpassword'xyz12345',dbendpoint''.allow public ip.

before launch configration create rds database.and add endpoint into dbenpoint userdata.

create auto scaling with this vpc and choose two private subnets both zones and launch.

create Load balancer with this vpc and choose public subnets both zones .

add all traffic with anywhere..

NOW search the Load Balancer DNS and logging into wordpress log in page..!


USE Service For AWS -- Load balance, RDS, Auto-Scliang, NAT Geteway, Elastic IP









![image](https://github.com/ajay-devop/Wordpress-userdata/assets/133880997/6c1268a1-e73c-4c9b-9406-fd14f63a2eb9)




