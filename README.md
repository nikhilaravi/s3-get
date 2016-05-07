# s3-get
An AWS lambda function that retrieves all the objects from an s3 bucket.

The incoming `event` object expects the following keys:

- bucket: the name of the s3 bucket.

It returns an array with all the file bodies e.g. if all the objects in the s3 bucket are `.json` files, it will return an array of JSON objects. 
