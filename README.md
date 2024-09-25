# AWS-Examples

This repository contains a collection of AWS examples used throughout AWS Certification Study Courses. These examples will guide you through common tasks and scenarios encountered in real-world AWS environments.

## Table of Contents
- [User Setup](#user-setup)
- [Group Setup](#group-setup)
- [AWS CLI Configuration](#aws-cli-configuration)
- [Testing AWS CLI Connection](#testing-aws-cli-connection)

## User Setup

To begin, you'll need to create a new user in your AWS account:

1. **Create User**: Use the AWS Management Console or the AWS CLI to create a user.
2. **Create Group & Assign Admin Permissions**: Create a new IAM group with `AdministratorAccess` permissions.
3. **Add User to Group**: Add the newly created user to the group with admin privileges.
4. **Generate Access Keys**: Generate an access key and secret key for the user. These will be used to authenticate through the AWS CLI.

## AWS CLI Configuration

Once you have the access and secret keys, set up the environment variables for AWS CLI authentication on Gitpod or any other environment.

```bash
$ export AWS_ACCESS_KEY_ID=AKIAIOSFODNN7EXAMPLE
$ export AWS_SECRET_ACCESS_KEY=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
$ export AWS_DEFAULT_REGION=us-west-2
