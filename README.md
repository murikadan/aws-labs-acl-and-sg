# aws-labs-acl -and-sg
 Cloudformation templates setting up a VPC with public and private subnet with necessary network components and instances. The set up is intended to be used for quickly creating an AWS lab set up which can be used for demonstrating how to set up route tables, acl's and sg's properly

 The permissions required for the lab user are mentioned in aws-labs-acl--and-sg\src\lab-user-permissions.txt. The custom policy used is included as lab-user-custom.json file. The custom policy is used to restrict the type of instances and in which region lab users are allowed to create instances so as to reduce the risk of users creating too many instances!

 See Practical\lab_notes.txt for more low level instructions on how to use the template/code.
