provider "aws" {
  region = "ap-south-1"

}
resource "aws_instance" "project" {
  ami           = "ami-0e742cca61fb65051"
  instance_type = "t2.micro"
  key_name = "dsa"
  tags = {
    Name = "server1"
  }

  }
