## DynamoDB Locking
This project is about locking tfstate file to prevent another developer to use the same code at at the same time .
Don t forget to add variable files for secret-access key
Create dynamoDB locking from the portal and add table name with locking key
Create S3 bucket to store your tfstate file 
This will remove the chance of conflict between developers updating same code
