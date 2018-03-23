- Comments on the usage of `Parameters`
- How was the lifecycle configuration created for the Auto Scaling Group?
- Using the security group Id (as opposed to security group name)
- Practices to follow when evolving a template
    - one change at a time
    - use change-sets
    - provisioning stacks from scratch versus updating stacks
- Aspects not covered:
    - `UpdatePolicy` for `AutoScalingGroup`
    - `cfn-signal`
    - `cfn-hup`