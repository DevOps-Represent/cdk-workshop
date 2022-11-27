# Setup Instructions
In this section, we're going to get everything we need ready to complete the workshop steps.

Here's what you'll need:
1. [Clone the repo to your local machine](#clone-the-repo-to-your-local-machine)
2. [Install project dependencies](#install-project-dependencies)
3. [Have a personal AWS account](#personal-aws-account)
4. [Install AWS CLI and auth via the command line](#install-the-aws-cli-and-auth-via-the-command-line)
5. [Have a code editor of your choice](#code-editor)

***

## Clone the Repo to your local machine
Clone this repo. You're going to make it your own and make edits. It's yours to keep and play around.

Choose a directory where you'd like to clone this repo to (it could even just be your desktop)

Run the following in your command line

`git clone git@github.com:DevOps-Represent/cdk-workshop.git`

If you don't have a GitHub account, download the zip folder of the repo:
[Repo Zip Download](https://github.com/DevOps-Represent/cdk-workshop/archive/refs/heads/main.zip)

## Personal AWS Account
If you don't already have one, you'll have to set up a personal AWS account. If you don't have one, having an AWS account is key if you intend on continuing your AWS learning journey after this workshop.

- If you DO have an account, log in *(preferably not as root and you've set up a user via IAM that has permissions to deploy resources)*

- If you DONT have an account, go [HERE](https://aws.amazon.com/) to create one, you'll need a credit card - Don't worry no cost will be incured today

## Install the AWS CLI and auth via the command line
As we're running commands via the command line that will allow you to deploy AWS resources, you need to authenticate to your personal AWS via the command line.

Here's install instructions for all operating systems: [How to install the AWS CLI 2](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)

Here's the instructions on how to authenticate via your command line:
NOTE: you'll need to get some details from the AWS web console that'll need to be copy and pasted for this to work
[AWS instructions on how to configure your command line](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html#cli-configure-quickstart-config)

It'll look something like this:
```
aws configure
```
Then following the prompts you need to provide:
- AWS Access Key ID
- AWS Secret Access Key
- Default region name (for Australia, choose ap-southeast-2)
- Default output format (you can just choose nothing)


## Code Editor
We're going to be writing and editing lines of Typescript code. To do this, it's best to use a code editor.

There's lots of free versions, here's a few to pick from if you don't already have one:

- [Visual Studio Code](https://code.visualstudio.com/) (recommended) - Provides out-of-the-box support for Typescript
- [Sublime Text 3](https://www.sublimetext.com/3)
- [Atom](https://github.com/atom)
- [Webstorm](https://www.jetbrains.com/webstorm/) - 30 day trial or paid license. Great IDE if you can get your company to pay for it.

Here's an even longer [list](https://hackr.io/blog/web-development-ide)


## NodeJS
The content in this workshop is written in Typescript, and requires NodeJS to run.

Download and install NodeJS

After you've successfully installed it, check that it's working by running the following in your command line:

```sh
node -v
```
It should print out the version of the Node runtime you installed.

## Install project dependencies
Now that you've installed Node, you should now be able setup the skeleton project.

The project uses npm for package management. To install the project packages, enter in your command line:

```sh
npm install
```

You should then see the following message if it's successful:
```
Successfully installed npm packages 👍
```
## [NEXT SECTION  - Key Concepts 👉🏽](01-key-concepts.md)
