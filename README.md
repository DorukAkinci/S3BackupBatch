# S3BackupBatch
When executed, the batch script copies the bucket files to the local storage with DateTime prefixed folder.

My main usage is for backup Cloudformation Template bucket but script can be changed for other purposes.

This batch is using ENV parameters to access AWS Credentials.

You have to install AWSCLI before execute the batch script.
