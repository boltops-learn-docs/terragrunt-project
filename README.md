<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terragrunt-project/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Simple Terragrunt Project

Simple Terragrunt Project is used to show how to migrate to Terraspace.

## Usage

Change the bucket in [terragrunt.hcl](terragrunt.hcl#L18) to a bucket that is available.

    cd us-east-1/dev/demo
    terragrunt apply -auto-approve
    cd -
    cd us-west-2/dev/demo
    terragrunt apply -auto-approve
    cd -

## Video

[![Watch the video](https://uploads-learn.boltops.com/bdhh9vbc0lrk90fih1482se9oa4d)](https://learn.boltops.com/courses/terraspace-and-terragrunt/lessons/terragrunt-to-terraspace-step-by-step-migration)
