# AWS-Passwordless

This is sample application for using the AWS Passwordless.

1.Clone the project
2.Do npm install
3.Get the AWS credentials and replace it in the AWS cognito client id in  SignIn.js
    Auth: {
        userPoolId: '<PoolId>',
        userPoolWebClientId: '<WebClientId>',
      }
4.Start the project using expo start 
5.Your ready to view the application using SMS login of AWS Cognito
