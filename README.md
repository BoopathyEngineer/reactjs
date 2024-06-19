create a dir use mkdir "" name the dir 
step one launch instance with required config

excample:
   choosing image ubuntu
   instance type : t2.micro
   key pair
   security group  with required port number
   volume 8 gb
after launch instance 
  login into by using this command     ssh -i aws_key.pem ubuntu@192.23.23.23
afterwards switch the user to root : root user only had full permission for the linux machine
install the nodejs using sudo apt install nodejs  if ubuntu user then  yum install nodejs for amazon linux user
