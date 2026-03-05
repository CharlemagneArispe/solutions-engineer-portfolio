# Day 7 – Scalable SaaS Architecture (AWS-style)

## Overview

This architecture demonstrates a scalable SaaS application design using AWS-style infrastructure components. The goal is to support high availability, horizontal scaling, and efficient handling of web traffic.

The architecture separates content delivery, application processing, database storage, and object storage layers.

---

## Architecture Diagram

![Architecture Diagram](architecture-diagram.png)

---

## System Flow

1. Users access the system through a web browser.
2. Requests first reach **CloudFront (CDN)**, which caches content closer to users.
3. Traffic is routed through an **Application Load Balancer** that distributes requests.
4. Requests are processed by multiple **EC2 instances** inside an **Auto Scaling Group**.
5. The application communicates with **Amazon RDS** for structured data.
6. Static assets such as images and media files are stored in **Amazon S3**.

---

## Components

### CloudFront
Content delivery network that reduces latency by caching content globally.

### Application Load Balancer
Distributes traffic across multiple compute instances.

### EC2 Auto Scaling Group
Runs application servers and automatically scales depending on traffic demand.

### Amazon RDS
Managed relational database used to store application data.

### Amazon S3
Object storage used for images, media, and static assets.

---

## Key Concepts Demonstrated

- Cloud architecture design
- Horizontal scaling
- Load balancing
- CDN usage
- Separation of compute and storage
- High availability

---

## Learning Outcome

This exercise demonstrates how scalable SaaS platforms can be structured using cloud infrastructure components. It highlights the importance of separating application layers to improve reliability and performance.
