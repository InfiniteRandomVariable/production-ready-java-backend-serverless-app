## realworld-serverless-application ![Build Status](https://codebuild.us-east-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoidk1hV1NVOVR6WkJSbjdEN3Evc0lDN2t1ZEQ2ZFVuTDV5Q1ZHMDF5NFZBZTBIWVZxbEtIN2w5NGNPRGxkQmpZVzJaQTVaV1I3Mm5tT1FYN1IxYmFGY1hBPSIsIml2UGFyYW1ldGVyU3BlYyI6Ijc2QU1Qc2lUTXY4Ny9Za2EiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=master)

Serverless app powered by Java-backend, a modification of AWS real world production-ready serverless application.

Utilized: Maven, Jue, unit testing, template, deployment stack, CDN.

What does the app do?
Step 1: Create account with password and email.
Step 2: An email will be sent upon account creation with a confirmation code.
Step 3: Input the confirmation code to authenticate the account.
Step 4: Login to account.
Step 5: Leading to a serverless application Repository that shows the current list of publication name created by the user. For new account, no such information can be available.
Step 6: Self-publishing/uploading the the text context, into a S3 server and be able to retrieve it upon correct account login.
Step 7: Sign out
Step 8: Repeat Step 4.

Current issues:
Error: Request failed with status code 400 - access control problem.



Follow this link to see the login example.
http://serverlessrepo-realworld-serverless-websitebucket-13kxgq4w0sg82.s3-website-us-east-1.amazonaws.com/#/

This project is an adaptation of the [AWS Serverless Application Repository](https://aws.amazon.com/serverless/serverlessrepo/). Its primary objective is to serve as a case study of how to build a real world application using a combination of serverless technologies and approaches. The project captures key architectural components, code structure, deployment techniques, testing approaches, and operational practices of the AWS Serverless Application Repository - a production-grade AWS service, written in Java and built using serverless technologies. It is comprised of 4 components.

![Architecture Diagram](https://github.com/awslabs/realworld-serverless-application/raw/master/images/architecture_diagram.png)

To get started, see the [Quick Start](https://github.com/awslabs/realworld-serverless-application/wiki/Quick-Start) guide. For more details, read our [blog post](https://aws.amazon.com/blogs/opensource/real-world-serverless-application) and see our [project wiki](https://github.com/awslabs/realworld-serverless-application/wiki).

## License

This project is licensed under the Apache-2.0 License.
