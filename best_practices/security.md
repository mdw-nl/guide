# Security

## Least Privilege

When working in platforms such as Azure portal and Github, ensure that all developers are given the minimal levels of permissions required for the work.

## Security by Design

Security measures should not be added late in the development process. Rather, it is taken into account from the start of the design and development process for any relevant application.

* Authentication and authorization are included early in the design and development process if required
* Time is taken during the design process to evaluate security flaws and risks
* During development, care is taken to never include environment information in code and tests. Paths, addresses and credentials are used in code only through configurable variables

## Security by Default

Applications are configured securely out of the box, without requiring additional configuration.

## Zero-Trust

Strict access controls are maintained for all required applications. Access requests to applications should be verified regardless of the origin.

## Data Transfer

For any publicly available service, data transfer is secured using end-to-end encryption to protect data in transit from interception and tampering.

## Federated Architecture

When working with sensitive data, design a federated architecture when possible to ensure data never leaves the customer's environment.

## Authentication and Authorization

If authentication and authorization is required for the application, avoid custom implementation if possible and opt for an existing, widely used open source third-party solution. Multi-Factor authentication should be implemented and enabled whenever possible.

### Product Authentication (IAAA)

Product authentication, encompassing Identification, Authentication, Authorization, and Accountability (IAAA), is correctly implemented to ensure that only legitimate users can access the system. Identification verifies the user's identity, authentication confirms it, authorization grants the appropriate level of access, and accountability tracks user actions. This comprehensive approach ensures robust security and traceability.

### Authentication Roles

Authentication roles are defined to ensure the proper isolation of data and information. By assigning specific roles and permissions, we can control access to sensitive data and functions, minimizing the risk of unauthorized access and data breaches. This role-based access control (RBAC) model helps maintain a secure and organized system.

### Input and Output Fields

All input and output fields, including switches, selections, and other interactive elements, are thoroughly tested to eliminate risks such as overflow, injection, and cross-site scripting (XSS). Proper validation and sanitization of inputs ensure that the system can handle unexpected or malicious data without compromising security. Rather than implementing these features, use established frameworks and libraries that allow for these features out of the box.
