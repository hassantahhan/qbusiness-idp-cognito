### Amazon Q Business application using Identity Federation through IAM Example

This repository provides a demonstration of how to use AWS CloudFormation automation to create a Q Business application with secure user authentication using IAM Identity Federation with Amazon Cognito. The repository can serve as an example from which readers can benefit when building automated solutions.

The CloudFormation template creates a basic infrastructure with the following key resources: 
 - **Cognito User Pool**: Manages user accounts and authentication, acting as an OpenID Connect (OIDC) identity provider (IdP).
 - **Cognito Identity Pool**: Provides temporary AWS credentials for authenticated users defined in the User Pool.
 - **QBusiness Application**: Offers a generative AI–powered assistant connected to an OIDC based identity provider.

Note: While the template code has been built with security in mind, you should still review all the policy definitions and resource configurations to ensure they suit your use case.
