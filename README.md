# CI, CD, CD

![](https://www.edureka.co/blog/content/ver.1531719070/uploads/2018/07/Asset-33-1.png)

### <b> Continuous Integration </b>
  - Each integration is verified by an automated build. With every push it tests, feedback is given. This is done through Jenkins.

### <b> Continuous Delivery </b>
  - To run automation passing the tests are key. In this stage, it leaves the code ready and waiting for deployment.

### <b> Continuous Deployment </b>
  - Also needs to pass tests in order for to be deployed and ready for usage. Usually for SAAS (Software as a Server)


![](https://agileforall.com/wp-content/uploads/2017/07/continuous-delivery-deployment.jpg)

#### Problems this piping may encounter:
- It works on my machine
- Code in the pipeline for 30 days
- Security/ Robustness
- Monitoring
- High capacity of users
- Main availability

# VPC

### <b> Virtual Private Network </b>

An isolated network in the cloud with <b>subnets</b> (network within a network) which allows to separate the resources you have when it comes to an internet access perspective.


![](https://docs.aws.amazon.com/vpc/latest/userguide/images/nat-instance-diagram.png)

#### Must remember:
- <b>Classless Inter-Domain Routing (CIDR)</b> - notation for IP address ranges
(e.g. 10.10.0.0/16 = fixes first 2 blocks (16 or 32)


- <b>Security Group (SG)</b> - Instance Level. attached to a VPC; every new instance launched is attached to a SG. Can only choose SG which are assigned ONLY to that VPC.
    - <b>Stateful</b> - meaning if you create an inbound rule allowing in traffic, that traffic is automatically allowed back out regardless of the outbound rule.
    - <b>Stateless</b> - traffic need to be specified back out.


- <b> Network Access Control list (NACL)</b> - a layer of security for your VPC that acts as a virtual firewall for controlling traffic in and out of one or more subnets.


- <b> Route table</b> - A route table contains a set of rules, called routes, that are used to determine where network traffic is directed. Each subnet in your VPC must be associated with a route table; the table controls the routing for the subnet.

#### NACL vs Security Group
- NACL supports allow and deny rules whereas security groups only support allow rules.
- NACL evaluates rules one at a time in order whereas security groups evaluates them all at the same time before it evaluates anything.

## Testing build on Jenkins (CI)
- CI testing :sushi:

## Testing connection build on Jenkins and notify email
- Testing notification

## Testing connection build on Jenkins and notify on Teams Jenkins Group
- Testing Teams
