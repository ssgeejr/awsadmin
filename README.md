# awsadmin

Scritps, commands, examples and more for setting up and using the various components of AWS


## S3

```
ioexcept:~$ aws configure
AWS Access Key ID [None]: <AWS_ACCESS_KEY>
AWS Secret Access Key [None]: <AWS_SECRET_KEY>
Default region name [None]: us-east-2
Default output format [None]: json
```


```
aws s3 ls
aws s3 cp s3_rw_policy.json s3://<BUCKET_NAME>
aws s3 ls s3://<BUCKET_NAME> --recursive --human-readable --summarize
```
