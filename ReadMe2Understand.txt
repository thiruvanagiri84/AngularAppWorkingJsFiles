Endpoint deployed in Ec2 with IP

http://18.216.103.153/organizations/1001/admins

When we call this from S3 bucket angularappwithIP, it will throw CORS error in the console. To resolve this temporarily, we need to add CORS enable extension to Chrome browser. Its specific to only Chrome browser. 

Permanent fix would be to use CloudFront service of AWS, which will enable 2 different hosts to be behaving as a single host.