# ecs_agent

Installs the ECS agent according to the second half of
[AWS documentation](http://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-agent-install.html)
The first half is taken care of by the reusable docker role

## Variables

* `ecs_agent_version` - version of ECS agent to run (defaults to latest)

## Requirements

Requires docker role to have been run
Uses yum and iptables, so only installs on RHEL-like installations.
