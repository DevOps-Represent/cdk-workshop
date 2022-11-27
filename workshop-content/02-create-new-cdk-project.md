# Create a new CDK project

```sh
npm install -g aws-cdk
cd src/infrastructure

cdk init app --language typescript
```

Before we dive in, let's get to know a little bit about the skeleton application CDK has created for us:

- `src/infrastructure/bin/infrastructure.ts` - Contains the code that initialises the App and Stack. It is the entry point for CDK and can be configured in `cdk.json`.
- `src/infrastructure/lib` - Where most of your infra code will live.
- `src/infrastructure/test` - Where unit tests for your infra code will live. This workshop will not focus on this area.
- `src/infrastructure/cdk.json` - The configuration file that CDK references for deploying your stack.

## [NEXT SECTION - CDK CLI ➡](03-cdk-cli.md)
