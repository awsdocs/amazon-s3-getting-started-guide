# Delete an Object and Bucket<a name="DeletingAnObjectandBucket"></a>



![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

If you no longer need to store the object that you uploaded and made a copy of while going through this guide, you should delete the objects to prevent further charges\.

You can delete the objects individually\. Or you can empty a bucket, which deletes all the objects in the bucket without deleting the bucket\. 

You can also delete a bucket and all the objects contained in the bucket\. However, if you want to continue to use the same bucket name, don't delete the bucket\. We recommend that you empty the bucket and keep it\. After a bucket is deleted, the name becomes available to reuse, but the name might not be available for you to reuse for various reasons\. For example, it might take some time before the name can be reused and some other account could create a bucket with that name before you do\.

**To delete an object from a bucket**

1. In the **Bucket name** list, choose the name of the bucket that you want to delete an object from\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/choose-bucket-name.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

1. In the **Name** list, select the check box next to the object that you want to delete, choose **More**, and then choose **Delete**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/more-menu-delete.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

1. In the **Delete objects** dialog box, verify that the name of the object you selected for deletion is listed, and then choose **Delete**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/objects-delete-confirm.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

You can empty a bucket, which deletes all the objects in the bucket without deleting the bucket\.

**To empty a bucket**

1. In the **Bucket name** list, choose the bucket icon next to the name of the bucket that you want to empty and then choose **Empty bucket**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/choose-empty-bucket.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

1. In the **Empty bucket** dialog box, type the name of the bucket for confirmation and then choose **Confirm**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/empty-bucket-confirm.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

You can delete a bucket and all the objects contained in the bucket\. 

**Important**  
If you want to continue to use the same bucket name, don't delete the bucket\. We recommend that you empty the bucket and keep it\. After a bucket is deleted, the name becomes available to reuse, but the name might not be available for you to reuse for various reasons\. 

**To delete a bucket**

1. In the **Bucket name** list, choose the bucket icon next to the name of the bucket that you want to delete and then choose **Delete bucket**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/choose-delete-bucket.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

1. In the **Delete bucket** dialog box, type the name of the bucket for delete confirmation and then choose **Confirm**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/images/delete-bucket-confirm.png)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)![\[Image NOT FOUND\]](http://docs.aws.amazon.com/AmazonS3/latest/gsg/)

Next, see [Where Do I Go From Here?](ImplementingS3.md)\.