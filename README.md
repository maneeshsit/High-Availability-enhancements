# High-Availability-enhancements
High Availability (HA) Enhancements for modern DC/AI DC and automotive infrastructures

## It’s a new physical-layer HA channel purpose-built for cluster heartbeat and quorum traffic that is:
- Independent of Ethernet fabric
- Independent of Top-of-Rack switches
- Independent of NIC drivers / TCP/IP stack
- Independent of VLAN / SDN misconfiguration
- Immune to broadcast storms, spanning tree issues, or congestion
- Physically constrained → inherently secure
- AWS EC2 Placement Groups
  -- In AWS, Placement Groups are a feature of Amazon EC2 that allows you to control how instances are placed on the underlying hardware. This is particularly useful for optimizing performance, fault tolerance, or workload distribution. There are three main placement strategies available, each tailored to specific use cases.
  https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/placement-groups.html
- Proposing a dedicated out-of-band RF heartbeat fabric inside the rack.


