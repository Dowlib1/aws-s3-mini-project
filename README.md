# aws-s3-mini-project
A demo of hands-on practice using the management console to interact with aws
##Login to your aws accounnt and search for 's3'
![iam](images/est.png)

##Locate and press 'create bucket'
![iam](images/est1.png)
##Enter the unigue name 

![iam](images/est2.png)
select ACL 
Select block all public access
click on 'disable version'
![iam](images/est3.png)
click on disable 'create button'
![iam](images/est4.png)


![iam](images/est5.png)
##On your desktop create a file 
![iam](images/est6.png)
##On aws s3 console click on upload
![iam](images/est7.png)
##add file, and upload
![iam](images/est8.png)
##Now tht the bucket has s been created, click on it
![iam](images/estr.png)

##select the file
![iam](images/estt.png)
##Edit the versioning
![iam](images/estq.png)
##Enable versioning
![iam](images/estsv.png)
##add text or modify the file
![iam](images/estw.png)
##upload and check to show versions
![iam](images/estp.png)
##set Allow permission
![iam](images/estg.png)
##uncheck 'Block all public access'
![iam](images/estcon.png)
##confirm oyur changes
![iam](images/estcc.png)
##now that the block access toall is off click on edit policy
![iam](images/estedit.png)
## Now, select the "Type of Policy" as "S3 Bucket
Policy"
a) Set the "Effect" to "Allow",
b) specify the "Principal" as "*" which means all users.
c) Choose the action "Get object " and "Get object
version",
d) In the field of Amazon Resource Name (ARN), type the
ARN of your bucket and add by "/*" after the ARN.
Then,
e) click on "Add statement".
![iam](images/estemp.png)

![iam](images/estarn.png)

![iam](images/esttemp.png)
##Copy the statment code and close the page
![iam](images/estpset.png)
##PAste the permission you copied to the permissions page and save changes
![iam](images/estest.png)
![iam](images/estes.png)
![iam](images/esd.png)
![iam](images/estwww.png)
##click the link
![iam](images/esdout.png)
##To create a lifecycle policy click on 'creaate lifecycle policy'
![iam](images/esdbu.png)
![iam](images/lie.png)

![iam](images/esdvicot.png)

![iam](images/est.png)
![iam](images/est.png)
