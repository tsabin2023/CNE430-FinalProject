# CNE430-FinalProject: Online Resume on AWS
## Project Overview
### Build and host an online resume on a secure web server using a range of AWS services: [S3](https://aws.amazon.com/s3/), [Route 53](https://aws.amazon.com/route53/), [CloudFront](https://aws.amazon.com/cloudfront/), and [AWS Certificate Manager](https://aws.amazon.com/certificate-manager/)to provide scalability, security, and reliability.
![figure #Architecture.jpg](Architecture.jpg)
## Build a S3 Static Website
* Create HTNL, CSS and JavaScript files for:
	- Main page
	- John Doe's Resume Page
	- Alex Johnson's Resume Page
	- Ryan Miller's Resume Page
* Create a S3 Bucket and upload fies to this bucket.
* Configure [S3](https://aws.amazon.com/s3/) to host a static website with public access.
## Associate the website with a custom domain name using [Route 53](https://aws.amazon.com/route53/)
* Create public hosted zone for the custom domain name on [Route 53](https://aws.amazon.com/route53/).
* Update Domain Name records to point to the [S3](https://aws.amazon.com/s3/) website endpoint
## Create TLS/SSL Certificate using [AWS Certificate Manager](https://aws.amazon.com/certificate-manager/)
* Using [AWS Certificate Manager](https://aws.amazon.com/certificate-manager/)us-east-1 region to issued certificate for custom domain name.
## Distribute the website by using [CloudFront](https://aws.amazon.com/cloudfront/)
* Setting up Origin Access Control to [CloudFront](https://aws.amazon.com/cloudfront/).
* Updating the A Record in [Route 53](https://aws.amazon.com/route53/) to point to [CloudFront](https://aws.amazon.com/cloudfront/)
## Special Thanks
Thank you, Christine Sutton, for all the guidance on this project and during the course.

