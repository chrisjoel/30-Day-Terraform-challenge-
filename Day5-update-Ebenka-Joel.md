# Day 5: Scaling Infrastructure

## Participant Details

- **Name:** Ebenka christian joel
- **Date and Time:** 31-08-2024 at 01:23 pm

## Task Description
**Blog Post ideas**: "mananging high traffic applications with aws elastic load balanacer and terraform, Best pratices for managing state files ".

https://medium.com/@hrcyvw/aws-elastic-load-balanacer-and-terraform-best-pratices-for-managing-state-files-8159d6436870


**terraform file for storing the state file**

backend.tf

```bash

terraform {
  backend "s3" {
    bucket = "30-days-challenge-joel"
    key    = "day5-Scaling-Infrastructure"
    region = "us-east-1"
  }
}

```

**architecture diagram**

!["Architecture of "](Highly-Available-Web-App-on-AWS-Using-Terraform.png)
