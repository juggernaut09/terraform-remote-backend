# terraform-remote-backend
This terraform project shows how to store terraform's tf.state file in Amazon s3(remote backend)


## Note:
Before configuring the terraform backe-end to use s3 to store state files do the following steps.


# step1:
Create the s3_bucket and dynamodb resources 

# step2:
*terraform init
*terrfaorm plan(Optional)
*terrfaorm apply

# step3:
Write the code to configure the terraform to use s3 as remote-backend
*terraform init (This time it is used to reinitialize the configuration. This command is idempodent i.e It wont effect your infrastructure no matter how many times you run it.)




