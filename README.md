# Summary
### Data product:<br> setting up a Tornado warning system with AWS Simple Notification System (SNS) using Python Boto 3.


<p>
This project uses the Simple Notification Service (SNS) of AWS. Several basic functions like creating topics, subscriptions, publishing are explained. These functions are used to set up a Tornado warning system, which sends warning messages about incoming tornados to email endpoints. There are two inputs into the SNS: a contact list of subscribers and a tornado information table. Depending on the speed of the Tornado, different messages are sent out to the endpoints . It is possible to develop the functionality of the warning system further.
</p>
    


<p> 
The project relies heavily on the  
<a href = https://boto3.amazonaws.com/v1/documentation/api/latest/index.html target=_blank> 
Boto3 documentation.</a> <br> 
According to the doc: 
</p> 

<p> 
“You use the AWS SDK for Python (Boto3) to create, configure, and manage AWS services, such as Amazon Elastic Compute Cloud (Amazon EC2) and Amazon Simple Storage Service (Amazon S3). The SDK provides an object-oriented API as well as low-level access to AWS services.” 
</p> 

<p>This project creates an  

### S3_helpers_pckg 

<p> 
The functionality is extended with a newly created helper package by me. This package is a work in progress. <br>
The package stores a class with useful helper functions, mostly manipulating the dicts of responses.<br> 
The functions are mostly self defined, but other functions for example from Github and the doc are integrated.<br> 
In this case credits are given.<br> 
The pckg is a work in progress. 
</p> 
