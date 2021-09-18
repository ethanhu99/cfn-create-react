# AWS CloudFormation Create React Template
A template file for creating a react website using S3 buckets, Cloudfront, CodeBuild, and CodePipeline.

## Usage

make                    - builds a zip file to target/.
make test               - execute the tests, requires a working AWS connection.

make deploy             - deploy to the default region eu-central-1.
make deploy-all-regions - deploy to all regions.

make release            - builds a zip file and deploys it to s3.

make deploy-provider    - deploys the provider.
make delete-provider    - deletes the provider.

make demo               - deploys the demo cloudformation stack.
make delete-demo        - deletes the demo cloudformation stack.

make clean              - the workspace.
