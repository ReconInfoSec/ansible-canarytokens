ansible-canarytokens
=========

An Ansible playbook to deploy Docker and canarytokens to Ubuntu 16.04. It deploys nginx with SSL using self signed certs.

More documentation can be found at the official canarytokens repos [here](https://github.com/thinkst/canarytokens) and [here](https://github.com/thinkst/canarytokens-docker).

Modify the hosts file and main.yml to fit your needs, then run the following:

```
ansible-playbook main.yml
```
