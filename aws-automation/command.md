# command to copy a single file into s3 bucket
aws s3 cp vpc s3://jenkins-terraform-aws/

# command to copy files into s3 bucket
aws s3 cp vpc s3://jenkins-terraform-aws/ --recursive

# command to list out files in s3 bucket
aws s3 ls s3://jenkins-terraform-aws/ --recursive

# command to delete files in s3 bucket
aws s3 rm s3://jenkins-terraform-aws/ --recursive


# command to move files into s3 bucket
aws s3 mv vpc s3://jenkins-terraform-aws/ --recursive

# now move files from s3 bucket to empty folder vp2
aws s3 mv s3://jenkins-terraform-aws/ vp2 --recursive
