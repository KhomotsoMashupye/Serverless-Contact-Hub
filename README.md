# Contact Form Serverless Website

## Description
This project demonstrates a fully serverless contact form website hosted on AWS. It uses S3 for static hosting, CloudFront for CDN and security, DynamoDB as the NoSQL database to store form submissions, Lambda functions for backend logic, and API Gateway to expose the Lambda via HTTP endpoints.

The website allows users to submit contact information and messages, which are securely stored in DynamoDB. This setup showcases how to build a scalable, secure, and cost-effective serverless web application on AWS.

---

## Architecture Overview

- *S3 Bucket*: Hosts the static website files (HTML, CSS, JavaScript).
- *CloudFront*: Distributes the website content with caching and security.
- *DynamoDB*: Stores contact form submission data in a NoSQL table.
- *Lambda Function*: Backend logic to receive form data and write to DynamoDB.
- *API Gateway*: HTTP API triggers the Lambda function from frontend requests.
- *IAM Users and Policies*: Secure user access and permissions setup.

---

## How to Use

1. Visit the website URL( http://awsmywebksm.s3-website.af-south-1.amazonaws.com)
2. Fill in the contact form with your name, email, and message.
3. Submit the form.
4. See the success message confirming your submission.
5. Data is stored in DynamoDB and can be accessed via AWS Console.

---

## Proof of Deployment (Screenshots)

1. Created S3 bucket with website files (HTML, CSS, JS)  
![Screenshot_19-5-2025_131812_af-south-1 console aws amazon com](https://github.com/user-attachments/assets/46907da7-f99c-47e6-a633-e00ae5b8557e)


2. S3 bucket policy setup  

![Screenshot_19-5-2025_132819_af-south-1 console aws amazon com](https://github.com/user-attachments/assets/f323803e-a6a3-4fc3-afae-27e1d29ebc5f)

3. CloudFront distribution  

![Screenshot_19-5-2025_143153_us-east-1 console aws amazon com](https://github.com/user-attachments/assets/66733308-356f-46a6-961e-f70498aa0fb8)

4. IAM Users list  

![Screenshot_19-5-2025_155151_us-east-1 console aws amazon com](https://github.com/user-attachments/assets/7cca7599-2702-4a8d-be2c-47bdb0267f2d)

5. IAM Policies attached  
![Screenshot_19-5-2025_15530_us-east-1 console aws amazon com](https://github.com/user-attachments/assets/2b58ee97-ca1d-4b1e-9054-e5ec415ee1f3)


6. DynamoDB ContactFormEntries table  
![Screenshot_19-5-2025_16053_af-south-1 console aws amazon com](https://github.com/user-attachments/assets/77ecb1d9-6e3a-41f8-8cd5-1883366105ac)


7. Lambda function code and configuration  
![Screenshot_19-5-2025_161925_af-south-1 console aws amazon com](https://github.com/user-attachments/assets/ea4b5c1d-0f43-460f-9810-3c3a518efaeb)


8. API Gateway HTTP API settings  
![Screenshot_19-5-2025_162833_af-south-1 console aws amazon com](https://github.com/user-attachments/assets/ee8b7e27-9348-45b4-a595-94207a4d6512)


9. Final website with successful message  

---![Screenshot_19-5-2025_164915_awsmywebksm s3-website af-south-1 amazonaws com](https://github.com/user-attachments/assets/fd1ef766-dda8-4046-9d7e-e2dbd456a5f8)

## COMPLETED
## MAY 2025
