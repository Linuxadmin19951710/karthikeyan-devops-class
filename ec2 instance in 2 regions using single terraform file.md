![terraform code](https://github.com/user-attachments/assets/0676da79-aae3-4112-a9a6-1555e7944d70)
![terraform terminal output](https://github.com/user-attachments/assets/eb5b354e-a633-4910-ab9d-174df001e881)
![us west 1](https://github.com/user-attachments/assets/df125124-76b3-4cb3-a7a6-1adaa1ebc4bf)
![ap south 1](https://github.com/user-attachments/assets/faeb9666-90d5-442a-b476-4f3779b9f8ba)


Configure aws cli before proceeding the below steps

provider "aws"  {
    region = "ap-south-1"
}

resource "aws_instance" "Newinstance" {
    ami = "ami-053b12d3152c0cc71"
    instance_type = "t2.micro"
    tags = {
        "Name" = "terraform1"
    }
  
}

provider "aws"  {
    region = "us-west-1"
    alias = "south"
}

resource "aws_instance" "Newinstance2" {
    ami = "ami-0657605d763ac72a8"
    instance_type = "t2.micro"
    provider = "aws.south"

    tags = {
        "Name" = "terraform2"
    }
  
}
