# Info
This repository contains a simple web application with automated deployment to AWS Elastic Beanstalk via CodePipeline and CodeBuild. The pipeline runs on every commit to main, builds, tests, and deploys a new version. 
Artifacts are stored in S3 and operations are monitored via CloudWatch. The live environment is temporarily paused. Run locally or activate the environment as needed.
