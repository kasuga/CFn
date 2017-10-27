# AWS CloudFromation Template
# About this template
This template is create for learning.

It can be moved individually as a stack, and it can be attached to existing ones.

If you want to move it in a series, please move it in the following order.

VPC → Network → EC2 → ElastiCache → RDS → ALBandAutoScaling → CloudFront

Aiso, Since it is recommended to use SSL, please issue certificate in advance and obtain domain at Route 53 in advance.
# Create List
- VPC
- Subnet
- NATGW & EIP
- EC2 (AutoScaling)
- RDS(Aurora)
- ElastiCache(Redis)
- ALB
- CloudFront