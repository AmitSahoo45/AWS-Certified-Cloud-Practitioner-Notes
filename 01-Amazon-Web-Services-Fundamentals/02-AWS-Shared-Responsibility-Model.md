## AWS Shared Responsibility Model

#### Overview
**Concept**: AWS Shared Responsibility Model defines responsibilities between AWS and customers in cloud service management.
**Graphic Representation**: Clarifies customer vs. AWS responsibilities.

### Customer Responsibilities (Top Layer)

**Data Management**:
a. Data ownership and protection are customer responsibilities.
b. Includes storage, databases, and data transmission services.

**Platform and Applications**:
1. Customer manages platform, applications, and access control (IAM).
2. AWS provides IAM services, but customer creates users, roles, policies, etc.

**Operating Systems**:
1. Customer manages OS updates, patches, network, and firewall configurations.
2. AWS may manage OS patches in some cases.

**Encryption and Security**:
1. Customer ensures data encryption at rest and in transit.
2. Utilizes AWS encryption features and network security tools.


### AWS Responsibilities (Bottom Layer)
**Infrastructure**:
1. AWS provides regions, availability zones, edge locations, and global infrastructure management.
2. Manages physical and network security at data centers.

**Services and Software**:
1. AWS manages compute, storage, database, networking services, and software layers.
2. Responsible for security of the cloud infrastructure and services.

### Key Points for Examination
1. Customer Responsibility: Data management, platform setup, access control, OS updates, encryption, and security configurations.
2. AWS Responsibility: Infrastructure management, global services, physical security, and software layers.
3. Understanding the Split: Essential to know what each party is responsible for to ensure effective cloud service management.
4. Additional Resources: Refer to AWS documentation for detailed information on the Shared Responsibility Model.