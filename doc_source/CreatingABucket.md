# Create a Bucket<a name="CreatingABucket"></a>



![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

Now that you've signed up for Amazon S3, you're ready to create a bucket using the AWS Management Console\. Every object in Amazon S3 is stored in a bucket\. Before you can store data in Amazon S3, you must create a bucket\. 

**Note**  
You are not charged for creating a bucket; you are charged only for storing objects in the bucket and for transferring objects in and out of the bucket\. The charges you will incur through following the examples in this guide are minimal \(less than $1\)\. For more information about storage charges, see [Amazon S3 Pricing](https://aws.amazon.com/s3/pricing/)\.

**To create an S3 bucket**

1. Sign in to the AWS Management Console and open the Amazon S3 console at [https://console\.aws\.amazon\.com/s3/](https://console.aws.amazon.com/s3/)\.

1. Choose **Create bucket**\.  
![\[Choose Create bucket.\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/create-bucket.png)

1. In the **Bucket name** field, type a unique DNS\-compliant name for your new bucket\. \(The example screen shot uses the bucket name admin\-created\. You cannot use this name because S3 bucket names must be unique\.\) Create your own bucket name using the follow naming guidelines: 
   + The name must be unique across all existing bucket names in Amazon S3\. 
   + After you create the bucket you cannot change the name, so choose wisely\. 
   + Choose a bucket name that reflects the objects in the bucket because the bucket name is visible in the URL that points to the objects that you're going to put in your bucket\.

   For information about naming buckets, see [ Rules for Bucket Naming](https://docs.aws.amazon.com/AmazonS3/latest/dev//BucketRestrictions.html#bucketnamingrules) in the *Amazon Simple Storage Service Developer Guide*\. 

1. For **Region**, choose US West \(Oregon\) as the region where you want the bucket to reside\.  

1. Choose **Create**\.  
![\[Create an S3 bucket page.\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/gsg-create-bucket-name-region.png)

You've created a bucket in Amazon S3\. 

