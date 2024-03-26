# new-express-app

## Using ECR to deploy an Application

[App runner](https://www.apprunnerworkshop.com/getting-started/)

```
Retrieve an authentication token and authenticate your Docker client to your registry.
Use the AWS CLI:

Build your Docker image using the following command. For information on building a Docker file from scratch see the instructions here .
You can skip this step if your image is already built:

After the build completes, tag your image so you can push the image to this repository:

Run the following command to push this image to your newly created AWS repository:

```

## Account Switching
[aws_switch](https://dev.to/hmintoh/how-to-use-multiple-aws-accounts-with-the-aws-cli-3lge#:~:text=To%20switch%20between%20different%20AWS,line%20via%20export%20AWS_PROFILE%3Dprofile_name%20.)



```
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": "ecr:*",
            "Resource": "*"
        }
    ]
}

```



