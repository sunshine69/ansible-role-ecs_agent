# ecs_agent

Installs ECS agent according to [AWS documentation](http://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-agent-install.html)

## Variables

* `ecs_agent_version` - version of ECS agent to run (defaults to latest)
* `ecs_agent_docker_version` - version of Docker CE to run (defaults to latest)

## Requirements

Uses yum and iptables, so only installs on RHEL-like installations.
