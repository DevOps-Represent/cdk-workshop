# Introduction to CDK
This section will cover the what and why of CDK. We will also cover key concepts that will be referenced throughout the workshop.

## What is CDK?
CDK (Cloud Development Kit) developed by AWS is a tool for building infrastructure/service as code on AWS. It's open source and is primarily maintained by AWS themselves.

It uses programming languages instead of languages commonly used for configuration such as JSON or YAML. CDK is available in TypeScript, Javascript, Python, Java, C# and Go.

## Why should I learn CDK?
- Infrastructure as code (IaC) is an important concept and is an in-demand skill for both software, data and platform engineers alike as organisations embrace devops.
- AWS, a major cloud provider, created CDK and is invested in it so you can be sure it's actively maintained. If there are people who know how to build tools for AWS, it's AWS.

## Key Concepts
- **Constructs** - Represents a "cloud component" and are the building blocks of your infrastructure.
- **Stacks** - Represents a deployable unit, often a group of related constructs. They are analogous to CloudFormation Stacks.
- **App** - Apps provide context to other constructs and allows you to create a shared scope for your Stacks. It's responsible for assembling your code into artifacts needed to deploy your code.

Stacks and Apps are special constructs that help you group everything together.

## [NEXT SECTION  - Create a new CDK project ➡](02-create-new-cdk-project.md)
