---
title: "Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1. </b> "
---

**On this page**, the worklog will summarize the entire journey of building an e-commerce website integrated with a Skin AI Analytic model and deploying the infrastructure on the AWS cloud platform. The program was completed within **12 weeks**. During those weeks, the work ranged from data collection, basic AWS infrastructure setup (S3, VPC, EC2), and database management (Prisma), to training and fine-tuning a Deep Learning model (EfficientNetB3), and finally deploying the entire system on AWS Amplify.

Typically and as a standard, a worklog is conducted over a period of about 3 months (throughout the internship) with the weekly content as follows:

**Week 1:** [Getting to know AWS and basic AWS services](1.1-week1/)

**Week 2:** [Learning Amazon S3, practicing creating Buckets, managing Objects, and configuring access permissions](1.2-week2/)

**Week 3:** [Collecting, processing, and building the storage structure for cosmetic image data on Amazon S3](1.3-week3/)

**Week 4:** [Collecting 50% of the dataset for the Skin AI model and building network infrastructure (VPC, EC2, NAT Gateway)](1.4-week4/)

**Week 5:** [Completing 100% of the dataset (Acne, Skintone, Wrinkles) and learning Load Balancing, Auto Scaling](1.5-week5/)

**Week 6:** [Syncing cosmetic images from S3 to the database using Prisma Studio and deploying CloudFront CDN](1.6-week6/)

**Week 7:** [Setting up the EfficientNetB3 architecture and sequentially training 4 skin condition classification models](1.7-week7/)

**Week 8:** [Evaluating results, debugging Overfitting, and fine-tuning Hyperparameters for the models](1.8-week8/)

**Week 9:** [Optimizing network architecture (CBAM) and loss function (Masked Focal Loss) to improve accuracy](1.9-week9/)

**Week 10:** [Integrating Softmax for a 5-point grading scale, exporting, and quantizing models to .tflite format](1.10-week10/)

**Week 11:** [Integrating the AI model to run directly on the browser (Client-side) and Deploying to AWS Amplify](1.11-week11/)

**Week 12:** [Performing comprehensive system testing, completing report documentation, and preparing for the project Demo presentation](1.12-week12/)