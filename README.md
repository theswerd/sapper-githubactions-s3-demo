# Sapper + Github Actions + S3
<img src="https://github.com/theswerd/sapper-githubactions-s3-demo/blob/main/banner.jpg?raw=true"></img>
Read how to create this repository from strach on your own (here)[https://swerdlowben.medium.com/automate-sapper-deployments-with-github-actions-d858e154dfb6]

This is a template repo that allows you to automatically deploy your **Sapper** app to S3 whenever there is a push to master with Github Actions.

# Setup

Add the following secrets to your repository:

1. The first secret will be your Access key ID, which you should name **AWS_ACCESS_KEY_ID**
2. Your second secret will be your Secret access key, which you should name **AWS_SECRET_ACCESS_KEY**
3. Your third secret will be your S3 location, which you should name **S3**. It should be formatted like **s3://yourbucket/**
