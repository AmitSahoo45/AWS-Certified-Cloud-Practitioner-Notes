### Server Virtualization Notes:

#### Traditional Server Setup:
- **Hardware Components**:
  - CPU (Processor)
  - RAM (Random Access Memory)
  - Storage
  - Network Adapter

- **Operating System (OS)**:
  - Linux, Windows, etc.

- **Applications/Services**:
  - Web server, database server, file server, etc.

- **Limitations**:
  - Tight integration between OS and hardware.
  - Non-portable OS and applications.
  - Underutilized resources lead to wasted capacity and higher costs.
  - Scalability constraints without horizontal scaling.

#### Virtualization Layer:
- **Hypervisor**:
  - Software layer on physical servers.
  - Examples: VMWARE, Zen, KVM, Microsoft Hyper-V.
  
- **Virtual Machines (VMs)**:
  - Created by the hypervisor, emulate physical resources.
  - Run operating systems and applications independently.

- **Benefits**:
  - Multiple VMs on one physical server.
  - Portability of VMs between servers.
  - Improved resource utilization, lower costs.
  - Scalability with quick deployment and capacity management.

#### Key Points:
- Hypervisor creates abstraction between physical server and VMs.
- VMs are portable, scalable, and efficient in resource utilization.
- Popular hypervisors include VMWARE, Zen, KVM, and Hyper-V.
- Server virtualization is fundamental to cloud services like AWS.