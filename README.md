<h2>Create a buildspec file for AWS CodePipeline to push to ECR</h2>

Let's start:

1. Pick code from github, here I have a python Django project
   code on my github account that i have cloned from another account.

2. Create an empty repo on ECR

3. Create a buildspec.yml file (aws codebuild understands only buildspec)
   Link: https://docs.aws.amazon.com/codebuild/latest/userguide/sample-docker.html

4. Add this buildspec file to your git repo so that I will login and push image to 
   Amazon Elastic Container Registry. (ECR)
   
5. Create an image of project on AWS CodeBuild

6. Attach IAM policies to auto-generate-role for codebuild project

7. Create a pipeline on AWS CodePipeline.

8. Check your ECR repo.

Thank You...
