Role amazon-ssm-agent
=========

Installs amazon-ssm-agent in ec2 instances (Amazon Linux 2)

Originally by AWS Docs: https://docs.aws.amazon.com/systems-manager/latest/userguide/agent-install-al2.html

Requirements
------------

There is no reqs.

Role Variables
--------------

You must change region values before execute installation task, see the Region column in Systems Manager service endpoints in the Amazon Web Services General Reference (https://docs.aws.amazon.com/general/latest/gr/ssm.html#ssm_region).
Example:
  package: https://s3.<your_region>.amazonaws.com/amazon-ssm-<your_region>/latest/linux_amd64

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: aws_servers
      roles:
         - ansible-amazon-ssm-agent

Author Information
------------------

Alex Mendes https://www.linkedin.com/in/mendesalex/
