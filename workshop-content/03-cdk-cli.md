# Deploy your first CDK app with CDK CLI

To proceed with this section, make sure you have your AWS account number on hand and make sure your AWS CLI credentials are configured.

We'll focus on commonly used commands and how you'll use them in conjunction with your code.

### ⚠ NOTE
We will be working from the `./src/infrastructure` directory. Make sure you navigate to it in your command line before running any of the commands below.

## `cdk bootstrap`
Before you can deploy anything with CDK, you must first "bootstrap" your AWS account. What this means is that CDK needs to deploy some resources and assign permissions in your account so that it's able handle interactions with AWS. You need to make sure you bootstrap the AWS account you intend to deploy to.

We'll stick to `us-east-1` as the region. Run the command below to bootstrap your AWS account.

```
npm run cdk bootstrap aws://YOUR-ACCOUNT-ID/us-east-1
```

## `cdk diff`
This command you to preview and compare the changes you've made to your project locally with the one deployed remotely.

Running `cdk diff` will output a list of AWS resources that will be updated, deleted or added should you deploy your changes.

Try the below command to see what kind of information is deployed with your stack.

```
npm run cdk diff
```

Now uncomment the example resource that AWS has provided in `lib/infrastructure-stack.ts` (lines 3 and 12-14) and run the diff command again.

## `cdk deploy`
Compiles your stacks and resources defined with CDK into CloudFormation templates.

It then deploys it to AWS.

```
npm run cdk deploy
```

## Further reading
[AWS CDK CLI offical documentation](https://docs.aws.amazon.com/cdk/v2/guide/cli.html)

## [NEXT SECTION  - Using custom constructs ➡](04-custom-constructs.md)
