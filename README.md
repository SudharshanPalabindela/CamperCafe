# CamperCafe
## Static Website in AWS

This repository contains the code for a static website designed and hosted in AWS. The website is built using HTML and CSS to create a responsive and visually appealing user interface.

## Features

- **Responsive Design:** The website is designed to be responsive, ensuring a seamless user experience across various devices and screen sizes.

- **AWS Hosting:** The website is hosted on AWS, leveraging the reliability and scalability of cloud services.

## Getting Started

### Prerequisites

- Git: [Download and Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- AWS Account: [Create an AWS account](https://aws.amazon.com/)

### Clone the Repository

```bash
git clone https://github.com/your-username/static-website-aws.git
```

## Local Development
Open the index.html file in your preferred web browser to view the static website locally.

## Deployment to AWS
- Create an S3 Bucket:
- create an S3 bucket to host the static website.

## Upload Contents to S3 Bucket:

```bash
aws s3 sync . s3://your-s3-bucket-name
```
`Replace your-s3-bucket-name with the name of your S3 bucket.`

## Configure S3 Bucket for Static Website Hosting:

- In the AWS Management Console, navigate to the S3 service.
- Select your S3 bucket.
- Go to the "Properties" tab.
- Enable "Static Website Hosting" and set the index document to index.html.
- Access the Website:
- Visit the provided S3 bucket URL to access your static website.

## License
- This project is licensed under the MIT License, making it open and free for anyone to use and modify.

## Contributing
- Feel free to contribute by submitting issues or pull requests. Your feedback and enhancements are welcome!

Acknowledgments
Inspiration: FreeCode Camp 

# Happy coding!
