### Amazon Q Business application using Identity Federation through IAM Example

This repository provides a demonstration of how to use AWS CloudFormation automation to create a Q Business application using IAM Identity Federation with Amazon Cognito. The repository is simplistic and does not aim to provide production-ready code but rather serves as an example from which readers can benefit when building automated solutions.

This CloudFormation template creates a basic infrastructure for a Q Business application using IAM Identity Federation with Amazon Cognito. The main resources created by this template include: 
 - **Cognito User Pool**: Manages user accounts and authentication, acting as an OpenID Connect (OIDC) identity provider (IdP).
 - **Cognito Identity Pool**: Provides temporary AWS credentials for authenticated users defined in the User Pool.
