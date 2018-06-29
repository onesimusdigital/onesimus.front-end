## Deploy to AWS

`ng build --prod --aot` this will build the angular src to the 'dist' folder

Log in to https://s3.console.aws.amazon.com/s3/buckets/onesimus
Delete the contents of the bucket
Upload contents of 'dist' folder
