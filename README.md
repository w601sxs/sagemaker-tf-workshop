# Workshop Lab Instructions

Instructions for the following labs are in the notebooks. Make sure you see the "Getting started" section below

- Prereq - Set up Studio (see instructions below)
- Lab 1 - https://github.com/aws/amazon-sagemaker-examples/tree/master/sagemaker-python-sdk/tensorboard_keras
- Lab 2 - https://github.com/aws/amazon-sagemaker-examples/blob/master/sagemaker-debugger/tensorflow_builtin_rule/tf-mnist-builtin-rule.ipynb
- Lab 3 - https://github.com/aws/amazon-sagemaker-examples/tree/master/training/distributed_training/tensorflow/data_parallel/mnist

> Note that Labs 1 through 3 are notebooks that are found in the main SageMaker example repository, and instructions to download and use these labs are included at the end of these instructions

## Getting Started

## Event Engine AWS Account access

Go to: https://dashboard.eventengine.run/login. You will be redirected to the page below.

![alt text](static/1.png)

Enter the event hash you have received from your instructor.

![alt text](static/2.png)

Click on Email One-Time Password (OTP).

![alt text](static/3.png)

You are redirected to the following page:

![alt text](static/4.png)

Enter your email address and click on Send passcode.

![alt text](static/5.png)

You are redirected to the following page:

![alt text](static/6.png)

Check your mailbox, copy-paste the one-time password and click on Sign in.

![alt text](static/7.png)

You are redirected to the Team Dashboard. Click on AWS Console.

![alt text](static/8.png)

On the next screen, click on Open AWS Console.

![alt text](static/9.png)

You are then redirected to the AWS Console.



## Amazon SageMaker Studio access

Amazon SageMaker Studio is a web-based, integrated development environment (IDE) for machine learning that lets you build, train, debug, deploy, and monitor your machine learning models. Studio provides all the tools you need to take your models from experimentation to production while boosting your productivity.

If the AWS Account has been provisioned by your AWS Instructor, follow the next steps to access the SageMaker Studio environment:

1. Open AWS console and switch to AWS region communicated by your instructor.

![alt text](static/11.png)

2. Under services search for Amazon SageMaker.

![alt text](static/12.png)

3. Under Get Started, click on the orange button SageMaker Studio.

![alt text](static/13.png)

4. A SageMaker Studio environment should already be provisioned. Click on Open Studio (on the right side of the preprovisioned sagemakeruser username).

![alt text](static/14.png)

5. The page can take 1 or 2 minutes to load when you access SageMaker Studio for the first time.

![alt text](static/15.png)

6. You will be redirected to a new web tab that looks like this:

![alt text](static/16.png)

7. Under Utilities and files click on System terminal

![alt text](static/17.png)

8. In the terminal, type the following command:

```
git clone https://github.com/aws/amazon-sagemaker-examples.git
```

9. After completion of step 8 you will have an "amazon-sagemaker-examples" folder created in left panel of the studio

10. All labs are placed inside the folders described below, and you can get now get started with Lab 1!

### Workshop labs structure 
(or, where to find the right labs...)

- Lab 1 - sagemaker-python-sdk/tensorboard_keras
- Lab 2 - sagemaker-debugger/tensorflow_builtin_rule
- Lab 3 - training/distributed_training/tensorflow/data_parallel/mnist

**Find and run the noteook (.ipynb file) in each of these folders**







