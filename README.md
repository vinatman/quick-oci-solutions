# Quick OCI Solutions

[![License: UPL](https://img.shields.io/badge/license-UPL-green)](https://img.shields.io/badge/license-UPL-green) [![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=oracle-devrel_test)](https://sonarcloud.io/dashboard?id=oracle-devrel_test)

## Introduction
A curated collection of quick, ready-to-use scripting and coding solutions for Oracle Cloud Infrastructure (OCI) across a range of services—especially focusing on use cases not natively supported by OCI tooling or that require custom integrations.

## Purpose
This repository helps cloud engineers, architects, and developers speed up automation efforts and solve practical challenges in OCI using bespoke scripts and code samples.

## What's Inside
🛠 Utilities: Helper scripts for automating routine OCI tasks
🧩 Integrations: Code for connecting OCI with third-party or external systems
📝 Workarounds: Solutions for gaps or missing features in native OCI services
📚 Usage Examples: Templates and sample code for common patterns
Supported Services
Solutions may cover—but are not limited to—these OCI services:

Compute
Object Storage
Networking (VCN, Load Balancer, etc.)
IAM
Database
Events & Functions
Monitoring & Logging
…plus integrations and extensions for external or non-native services.

### Prerequisites
Before using the scripts and solutions in this repository, please ensure you have the following set up:

1. Oracle Cloud Account
An active Oracle Cloud Infrastructure (OCI) account .
Permissions to perform the relevant operations (compartment, resource, and service-specific access).
2. API Credentials
A valid OCI user with API signing keys configured (typically stored in ~/.oci/config).
How to create an API key and config file (Oracle Docs)
3. Command-Line Tools & SDKs
Depending on the script’s language and target service, you may need:

- OCI CLI (oci)
- Python 3.x and OCI Python SDK (pip install oci)
- Bash, jq, curl (for shell scripts)
- OCI SDKs (Python, Java, etc.), as specified in individual script folders
4. Network Access
Scripts may need connectivity to OCI public endpoints or your tenancy’s private endpoints, depending on your setup.
5. Environment Variables
Some solutions may require setting environment variables (like tenancy/compartment OCIDs, region, etc.). Refer to each script’s documentation for specifics.

Note:

Review and tailor scripts for security requirements.
Never share your OCI credentials or sensitive data.
Test scripts in non-production environments whenever possible.

## Usage
Clone this repo as needed
Browse the folders by service or use case.
Review any prerequisites noted in the README of each solution.
Run the scripts as directed. Most solutions are written in OCI CLI, SDKs using Python/other common scripting languages, and/or terraform.
Note: Always review code and adapt credentials or environment-specific values as needed!


## Contributing
<!-- If your project has specific contribution requirements, update the
    CONTRIBUTING.md file to ensure those requirements are clearly explained. -->

This project welcomes contributions from the community. Before submitting a pull
request, please [review our contribution guide](./CONTRIBUTING.md).
- Clearly document requirements, usage, and limitations
- Ensure your code follows security and privacy best practices

## Security

These scripts are provided "as-is". Before use, validate all scripts for security and compliance requirements relevant to your organization. Do not share sensitive credentials or data.

Please consult the [security guide](./SECURITY.md) for our responsible security
vulnerability disclosure process.

## License
Copyright (c) 2024 Oracle and/or its affiliates.

Licensed under the Universal Permissive License (UPL), Version 1.0.

See [LICENSE](LICENSE.txt) for more details.

ORACLE AND ITS AFFILIATES DO NOT PROVIDE ANY WARRANTY WHATSOEVER, EXPRESS OR IMPLIED, FOR ANY SOFTWARE, MATERIAL OR CONTENT OF ANY KIND CONTAINED OR PRODUCED WITHIN THIS REPOSITORY, AND IN PARTICULAR SPECIFICALLY DISCLAIM ANY AND ALL IMPLIED WARRANTIES OF TITLE, NON-INFRINGEMENT, MERCHANTABILITY, AND FITNESS FOR A PARTICULAR PURPOSE.  FURTHERMORE, ORACLE AND ITS AFFILIATES DO NOT REPRESENT THAT ANY CUSTOMARY SECURITY REVIEW HAS BEEN PERFORMED WITH RESPECT TO ANY SOFTWARE, MATERIAL OR CONTENT CONTAINED OR PRODUCED WITHIN THIS REPOSITORY. IN ADDITION, AND WITHOUT LIMITING THE FOREGOING, THIRD PARTIES MAY HAVE POSTED SOFTWARE, MATERIAL OR CONTENT TO THIS REPOSITORY WITHOUT ANY REVIEW. USE AT YOUR OWN RISK. 

## Issues & Questions
If you find a bug or need assistance, please open an issue in this repo.

Happy automating on OCI! 🚀
