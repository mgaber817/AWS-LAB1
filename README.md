**AWS Lambda Power Tuning**

<img width="1911" height="923" alt="aws-lambda-power-tuning" src="https://github.com/user-attachments/assets/e7584a1a-a42b-4d96-b2a2-7dc8e8a48e2d" />


Welcome to an exciting lab to validate the different configs of a Lambda function to find the best combination between performance and best cost.

What I built is a a simple serverless setup where API GW invokes a lambda that can write to a DynamoDB.
![alt text](image.png)

the catch is to use

AWS Lambda Power Tuning is a state machine powered by AWS Step Function that helps optimize lambda function for cost and performance in data driven way. This state machine is programming language agnostic and designed in such a way that its easy to use/deploy and fast to execute.

Now , I did a load test with Postman with virtual users and 3 minutes of testing: the key point is to check the "average response time"
<img width="1963" height="667" alt="image" src="https://github.com/user-attachments/assets/77471a19-d364-4457-b39f-d5b2776fe206" />
the results 
<img width="1432" height="885" alt="ramp_up_testing-128" src="https://github.com/user-attachments/assets/46b2165f-7a95-4334-8419-21a894ad6717" />



