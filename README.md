# My_first_projec
Create an a EC2 instance <br>
resource "aws_instance" "my_ec2" {<br>
  ami           = "resolve:ssm:/aws/service/ami-amazon-linux-latest/al2023-ami-kernel-default-x86_64"<br>
  instance_type = "t2.micro"<br>

  tags = {<br>
    Name = "HelloWorld"<br>
  }<br>
}<br>
