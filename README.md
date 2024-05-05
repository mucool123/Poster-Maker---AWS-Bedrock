# 🎬 Custom Poster Generator

Welcome to the repository for the Custom Poster Generator project! This application leverages the power of Generative AI through AWS Bedrock, specifically using the Stability AI's Foundation Model to generate posters based on user inputs.

## 📌 Project Overview

![app1 drawio](https://github.com/mucool123/Poster-Maker---AWS-Bedrock/assets/59078822/ce097dfe-103d-4ea2-9f02-896f8b724437)


This project creates a system where users can generate custom posters by providing a creative prompt via a REST API. Here's a brief on how it functions:

- **User Input**: The user provides a prompt describing their desired poster through a REST API.
- **AWS API Gateway**: This prompt is routed via AWS API Gateway, triggering an AWS Lambda function.
- **Lambda Function**: Processes the prompt and sends it to AWS Bedrock.
- **Stability AI Foundation Model**: Utilized within Bedrock to generate the image.
- **AWS S3**: The generated image is stored in an S3 bucket.
- **Secure Access**: A pre-signed URL for the image is generated for secure and temporary access.
- **Result Delivery**: The URL is sent back to the user, enabling them to view or share their custom poster.

## 🛠️ Technologies Used

- ![AWS](https://img.shields.io/badge/AWS-Bedrock-orange)
- ![Lambda](https://img.shields.io/badge/AWS-Lambda-yellow)
- ![API Gateway](https://img.shields.io/badge/API%20Gateway-Active-blue)
- ![S3](https://img.shields.io/badge/AWS-S3-blue)

## 🚀 Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- AWS account
- Configure AWS CLI with appropriate permissions

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/mucool123/Poster-Maker---AWS-Bedrock.git
2. **Set up AWS API Gateway and Lambda** according to the AWS documentation.
3. **Configure an S3 bucket** for storing the generated images.
4. **Update Lambda function** to interact with AWS Bedrock and S3.

### Usage

Send a prompt through the REST API to generate your custom poster. Access the returned pre-signed URL to view or download your poster.

## 🔍 Learning Outcomes

- Integration of AWS services (API Gateway, Lambda, S3, and Bedrock).
- Exploring generative AI capabilities for creative content generation.
- Handling security and access management with pre-signed URLs.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📫 Contact

Your Name - gharpuremukul786@gmail.com

Project Link: [https://github.com/mucool123/Poster-Maker---AWS-Bedrock](https://github.com/mucool123/Poster-Maker---AWS-Bedrock)
