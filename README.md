# Onfinality Terraform Plugin

This is a terraform provider of onfinality, so our user can manage their nodes on onfinality the same way they manage their other infrastracture

# Platform
terraform 0.15.x

# Usage
```
terraform {
  required_providers {
    aws = {
      source  = "onfinality/onf"
      version = "~> 1.0"
    }
  }
  provider "onfinality" {
      workspace = 1234567890123
  }

}
```

# Resources 
## Node
CRUD

## NetworkSpec
CRUD

# Data Sources
## Node

## NetworkSpec

## Cluster

## NodeSpec

# References
- onfinality cli: https://github.com/OnFinality-io/onf-cli
- onfinality api: https://doc.onfinality.io
- https://github.com/hashicorp/terraform-plugin-sdk
- https://www.hashicorp.com/blog/writing-custom-terraform-providers
- https://learn.hashicorp.com/tutorials/terraform/provider-use?in=terraform/providers

