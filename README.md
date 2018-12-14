ansible-canarytokens
=========

An Ansible playbook to deploy Docker and canarytokens to Ubuntu 16.04. It deploys nginx with SSL using self signed certs.

You will need a TLD with nameservers pointing to the IP or address of your canarytokens server, which will be what you put in your `switchboard.env`.

More documentation can be found at the official canarytokens repos [here](https://github.com/thinkst/canarytokens) and [here](https://github.com/thinkst/canarytokens-docker).

Modify the hosts file and main.yml to fit your needs, then run the following:

```
ansible-playbook main.yml
```
