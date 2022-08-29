subscription-manager w/ activation key
=========

Role to start/stop EC2 instance(s) and conditionally associate/disassociate elastic IP(s) to the same.  

Requirements
------------
- Python 2.7
- boto
- AWS access keys with EC2FullAccess privileges

Variables w/ Survey
--------------

- activationkey: Label generated from access.redhat.com/subscriptions >> management/activation keys
- org: Your org id, gathered from access.redhat.com/subscriptions

Example Playbook
----------------



Author Information
------------------
This playbook was created in 2022 by [Raul Leite](https://github.com/sp4wnr0ot "Github")
Twitter Handle: [@sp4wnr0ot](https://twitter.com/sp4wnr0ot "Twitter")
