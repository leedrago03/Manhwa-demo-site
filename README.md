# Manhwa Demo Website

## Overview
This project is a simple web application that displays a list of manhwa titles, their genres, and descriptions. The application is inspired by the article **"The 50 Best Fantasy Manhwa You Must Read Now."** 

To ensure high availability and scalability, the application leverages **Amazon EC2 Auto Scaling** and **Load Balancers**:
- **Auto Scaling**: Automatically adjusts the number of EC2 instances based on traffic demands, ensuring that the application can handle varying loads while optimizing costs.
- **Load Balancer**: Distributes incoming traffic across multiple EC2 instances to enhance availability and fault tolerance, ensuring that no single instance is overwhelmed with requests.

The application showcases a responsive design and retrieves images from an Amazon S3 bucket.

## Features
- Display a list of manhwa titles with genres and images.
- Responsive design for optimal viewing on different devices.
- Utilizes Amazon S3 for image storage.
- Deployed on AWS with auto-scaling and load balancing for better performance.

## Screenshot
![Screenshot from 2024-10-11 19-23-23](https://github.com/user-attachments/assets/ee53a52e-da4f-4eb9-9199-61e596b14986)
 
*Above is a screenshot of the live website.*

## Technologies Used
- **HTML**: For the structure of the web pages.
- **CSS**: For styling the web application.
- **JavaScript (if applicable)**: For any interactive features (not mentioned in the current structure).
- **Amazon S3**: For storing images used in the application.
- **AWS EC2**: For hosting the web application.
- **AWS Auto Scaling**: To dynamically adjust the number of running instances based on demand.
- **AWS Load Balancer**: To distribute incoming traffic evenly across instances.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
