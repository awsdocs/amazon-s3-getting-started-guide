# Create a Bucket<a name="CreatingABucket"></a>

Now that you've signed up for Amazon S3, you're ready to create a bucket using the AWS Management Console\. Every object in Amazon S3 is stored in a bucket\. Before you can store data in Amazon S3, you must create a bucket\. 

**Note**  
You are not charged for creating a bucket\. You are charged only for storing objects in the bucket and for transferring objects in and out of the bucket\. The charges that you incur through following the examples in this guide are minimal \(less than $1\)\. For more information about storage charges, see [Amazon S3 Pricing](https://aws.amazon.com/s3/pricing/)\.

**To create an S3 bucket**

1. Sign in to the AWS Management Console and open the Amazon S3 console at [https://console\.aws\.amazon\.com/s3/](https://console.aws.amazon.com/s3/)\.

1. Choose **Create bucket**\.  
![\[Console screenshot showing the Create bucket button.\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/create-bucket.png)

1. In the **Bucket name** box, enter a unique DNS\-compliant name for your new bucket\. 

   The example screenshot uses the bucket name `admin-created`\. You can't use this name because S3 bucket names must be unique\. Create your own bucket name using the following naming guidelines: 
   + The name must be unique across all existing bucket names in Amazon S3\. 
   + After you create the bucket, you cannot change the name, so choose wisely\. 
   + Choose a bucket name that reflects the objects in the bucket because the bucket name is visible in the URL that points to the objects that you're going to put in your bucket\.

   For information about naming buckets, see [ Rules for Bucket Naming](https://docs.aws.amazon.com/AmazonS3/latest/dev//BucketRestrictions.html#bucketnamingrules) in the *Amazon Simple Storage Service Developer Guide*\. 

1. For **Region**, choose US West \(Oregon\) as the Region where you want the bucket to reside\.  

1. Choose **Create**\.  
![\[Console screenshot showing the Create button on the Create an S3 bucket page.\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/gsg-create-bucket-name-region.png)

You've created a bucket in Amazon S3\. 

To add an object to your bucket, see [Add an Object to a Bucket](PuttingAnObjectInABucket.md)\.