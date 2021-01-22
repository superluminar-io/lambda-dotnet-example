# Lambda .NET Example

This is a simple example project bootstrapping a CDK project with C#. The goal is to create and deploy a lambda function.

## Prerequisites
* [NodeJS / NPM](https://nodejs.org/en/)
* [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)
* [Dotnet](https://dotnet.microsoft.com/download)
* [Dotnet Lambda CLI](https://docs.aws.amazon.com/lambda/latest/dg/csharp-package-cli.html)

## Getting started

Before deploying the application, make sure you have AWS credentials in your terminal.

```sh
$ git clone git@github.com:superluminar-io/lambda-dotnet-example
$ cd lambda-dotnet-example
$ make dependencies
$ make deploy
```

Use the URL from the stack output:
```
$ curl https://XXXXXXXXXX.execute-api.eu-central-1.amazonaws.com/prod/
```

## Credits

This project is based on the [AWS CDK Workshop](https://cdkworkshop.com/40-dotnet.html).