# Create a new CDK project

Run the following commands line-by-line to create a new CDK project.

```sh
npm install -g aws-cdk              # install the AWS CDK CLI
mkdir src/infrastructure            # create a new directory called "infrastructure" under "src"
cd src/infrastructure               # navigate to the infrastrcture directory
cdk init app --language typescript  # initialise a new CDK app in TypeScript
```

You should now see a lot of new files in the `infrastructure` directory.

## What's in our project?

Before we dive in, let's get to know a little bit about the skeleton application CDK has created for us:

- `src/infrastructure/bin/infrastructure.ts` - Contains the code that initialises the App and Stack. It is the entry point for CDK and can be configured in `cdk.json`.
- `src/infrastructure/lib` - Where most of your infra code will live.
- `src/infrastructure/test` - Where unit tests for your infra code will live. This workshop will not focus on this area.
- `src/infrastructure/cdk.json` - The configuration file that CDK references for deploying your stack.

## [NEXT SECTION - CDK CLI ➡](03-cdk-cli.md)
