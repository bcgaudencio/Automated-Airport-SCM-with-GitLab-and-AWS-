# Automated-Airport-SCM-with-GitLab-and-AWS-
 Automated supply chain management system for an airport's supply chain using GitLab and AWS, integrating inventory systems with real-time data processing through AWS IoT Core and advanced data analytics for informed decision-making. Leveraged GitLab's CI/CD pipeline and AWS CloudWatch for continuous monitoring and updates

# Automated Supply Chain Management System for Airports

This repository contains the code and documentation for an automated supply chain management system designed for airports. The system integrates advanced AWS services and GitLab CI/CD pipelines to manage and optimize airport supply chains efficiently.

## System Overview

The system leverages AWS IoT Core, DynamoDB, Lambda, Kinesis, and QuickSight to handle real-time data processing, inventory management, and decision-making insights, all backed by robust monitoring and security measures.

## Features

- **Real-Time Data Processing**: Integrates with AWS IoT for real-time data collection and processing.
- **Dynamic Inventory Management**: Uses DynamoDB for storage and Lambda for inventory level updates.
- **Data Analytics**: Utilizes AWS QuickSight for visualizing and analyzing data.
- **Automated Monitoring**: Employs AWS CloudWatch and SNS for system monitoring and alerts.
- **Continuous Deployment**: Facilitates updates and maintenance through GitLab CI/CD pipelines.

## Architecture

The architecture includes multiple AWS services interacting via APIs with an IoT-enabled environment for real-time data capture and analysis. Diagrams and further details can be added here.

## Prerequisites

- AWS Account
- GitLab Account
- AWS CLI installed
- Docker installed (for containerized services)
- Python 3.x

## Installation

Follow these steps to set up the system:

### 1. Clone the repository



bash
git clone https://github.com/yourusername/automated-supply-chain.git
cd automated-supply-chain


### 2. Set up AWS Services

Detailed instructions for setting up each AWS service used in this project are provided in their respective directories. These include configurations for:

- AWS IoT
- DynamoDB
- Lambda
- Kinesis
- QuickSight

### 3. Deploy with GitLab CI/CD

Ensure your GitLab CI/CD pipeline is properly set up to handle deployment. The `.gitlab-ci.yml` file in the root directory contains all necessary configuration.

## Usage

After installation, the system will process data as configured. You can monitor outputs and logs through AWS CloudWatch and visualize data in AWS QuickSight.

## Contributing

Contributions are welcome! Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests to us.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Gaudencio Benitez– bcgaudencio@gmail.com

Project Link: [https://github.com/bcgaudencio/Automated-Airport-SCM-with-GitLab-and-AWS-)

## Acknowledgments

- AWS documentation
- GitLab CI/CD documentation



