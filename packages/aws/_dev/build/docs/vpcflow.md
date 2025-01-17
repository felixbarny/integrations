# vpcflow

## Logs

Module for the AWS virtual private cloud (VPC) logs which captures information
about the IP traffic going to and from network interfaces in VPC. These logs can
help with:

* Diagnosing overly restrictive security group rules
* Monitoring the traffic that is reaching your instance
* Determining the direction of the traffic to and from the network interfaces

Implementation based on the description of the flow logs from the
documentation that can be found in:

* Default Flow Log Format: https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html
* Custom Format with Traffic Through a NAT Gateway: https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs-records-examples.html
* Custom Format with Traffic Through a Transit Gateway:
  https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs-records-examples.html

{{fields "vpcflow"}}

{{event "vpcflow"}}
