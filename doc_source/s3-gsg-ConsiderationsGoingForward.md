# Considerations Going Forward<a name="s3-gsg-ConsiderationsGoingForward"></a>

**Topics**
+ [AWS Account and Security Credentials](#iam-about-shared)
+ [Security](#s3-gsg-Security)
+ [AWS Integration](#s3-gsg-AWSIntegration)
+ [Pricing](#s3-gsg-Pricing)

This section introduces you to topics you should consider before launching your own Amazon S3 product\.

## AWS Account and Security Credentials<a name="iam-about-shared"></a>

When you signed up for the service, you created an AWS account using an email address and password\. Those are your AWS account root user credentials\. As a best practice, you should not use your AWS account root user credentials to access AWS\. Nor should you give your credentials to anyone else\. Instead, create individual users for those who need access to your AWS account\. Create an AWS Identity and Access Management \(IAM\) user for yourself as well, give that user administrative privileges, and use that IAM user for all your work\. For information about how to do this, see [Creating Your First IAM Admin User and Group](https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started_create-admin-group.html) in the *IAM User Guide*\.

If you're an account owner or administrator and want to know more about IAM, see the product description at [https://aws\.amazon\.com/iam](https://aws.amazon.com/iam) or the technical documentation in the [IAM User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/)\.

## Security<a name="s3-gsg-Security"></a>

Amazon S3 provides authentication mechanisms to secure data stored in Amazon S3 against unauthorized access\. Unless you specify otherwise, only the AWS account owner can access data uploaded to Amazon S3\. For more information about how to manage access to buckets and objects, go to [Managing Access Permissions to Your Amazon S3 Resources](https://docs.aws.amazon.com/AmazonS3/latest/dev/s3-access-control.html) in the *Amazon Simple Storage Service Developer Guide*\. 

You can also encrypt your data before uploading it to Amazon S3\.

## AWS Integration<a name="s3-gsg-AWSIntegration"></a>

You can use Amazon S3 alone or in concert with one or more other Amazon products\. The most common products used with Amazon S3 are:
+ [Amazon EC2](https://aws.amazon.com/ec2/)
+ [Amazon Elastic MapReduce](https://aws.amazon.com/elasticmapreduce/)
+ [Amazon SQS](https://aws.amazon.com/sqs/)
+ [Amazon CloudFront ](https://aws.amazon.com/cloudfront/)

## Pricing<a name="s3-gsg-Pricing"></a>

Learn the pricing structure for storing and transferring data on Amazon S3\. For more information, see [Amazon S3 Pricing](https://aws.amazon.com/s3/pricing/)\.