Project Summary: This project focuses on setting up a virtualized data center network environment using VirtualBox and OpenStack to demonstrate the communication between tenant virtual machines (VMs) through overlay and underlay networks. The project also implements security measures like microsegmentation to control VM communication based on their roles.

The implementation involves creating and configuring virtual gateways using VyOS to route traffic, setting up virtual networks with Geneve encapsulation, and configuring routers to connect tenant subnets. The environment supports tenant networks with internal and public interfaces and provides a secure and isolated communication mechanism.

The VMs, which are deployed using OpenStack, are assigned floating IP addresses to allow external access. The project also emphasizes the importance of live migration of VMs across hypervisors with minimal disruption, showcasing the resilience of the network infrastructure.
