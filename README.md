# Newgen

uses:
boto3
gunicorn

note:
-aws account has been configured through commandline
-s3 should have bucket 'newgen' (erro handling needs to be implemented)
-code deployment on ec2 
-postman implementation is remaining; currently url can be used for minimal testing

run steps:
- browse to project directory
- $gunicorn menu:app
- make requests through url (root '/' path will show the menu)
