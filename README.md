# AWS S3 Remote State Terraform Module

A Terraform module to set/pull remote state from an AWS S3 bucket.

## Module Input Variables

- `bucket` - The name of the S3 bucket holding remote state. 
- `key` - The path to the state file inside the bucket.
- `region` - The region of the S3 bucket.
