```hcl

provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "<github-aredo01>/docker-instance/aws"
    key_name = "Chris"
}
```

