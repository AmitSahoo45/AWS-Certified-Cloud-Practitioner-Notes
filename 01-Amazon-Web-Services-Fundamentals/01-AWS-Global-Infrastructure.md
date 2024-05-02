1. Regions and Availability Zones:
a. Regions are separate physical locations around the world.
b. Each region has multiple availability zones (usually at least three), which are one or more physical data centers.
c. Resources can be spread across availability zones for increased fault tolerance.

2. AWS Global Network:
a. Connects all regions worldwide, managed by AWS for high bandwidth and low latency.
b. Redundant networking within each region ensures reliable connectivity.

3. Other Infrastructure Components:
a. AWS Outposts: Hardware for running AWS services in corporate data centers.
b. Local Zones: Similar to availability zones, located in metropolitan areas for lower latency.
c. Wavelength Zones: Designed for 5G applications, reduce latency for mobile services.

4. Region Details:
a. Each region contains multiple availability zones, which in turn can have subnets for resource deployment.
b. Subnets can be public (accessible from the internet) or private (no direct external connectivity).
c. Redundancy in power sources and networking within availability zones ensures high availability.

5. Amazon CloudFront:
a. Content Delivery Network (CDN) caching content globally for improved performance and lower latency.
b. Ensures users can access content from locations closer to them.

6. AWS Deployment Advantages:
a. Easy global deployment of services using AWS management console, CLI, or API.
b. Simplified redundancy and data synchronization compared to traditional data center deployments.

----------------------------------------------------------

1. Regions:
Separate physical locations worldwide.
Multiple availability zones (usually ≥3) per region, e.g., us-east-1 has 6.

2. Availability Zones (AZ):
One or more physical data centers, offering redundancy.
Resources can be spread across AZs for high availability.

3. AWS Global Network:
Connects all regions, ensuring bandwidth and managing latency.

4. Networking within Regions:
Redundant networking capabilities within regions.

5. AWS Outposts:
Hardware for on-premises use, supporting selected AWS services.

6. Local Zones:
Similar to AZs, located in metropolitan areas for lower latency.

7. Wavelength Zones:
Designed for 5G applications, reducing latency.

8. Region Redundancy:
AZs within regions ensure redundancy and low latency.

9. Subnets:
IP networking spaces within AZs, offering public or private accessibility.

10. Redundancy:
Redundant power sources and networking within and between AZs.

11. High Availability:
Failover capabilities between AZs for quick recovery.

12. Disaster Recovery:
Separate regions for geographically distant application copies.

13. Amazon CloudFront:
Content Delivery Network (CDN) caching content globally for lower latency.

14. Deployment Flexibility:
Easily deploy resources globally using AWS management tools.
Simplified setup for redundancy and data synchronization.


----------------------------------------------------------
