## What is ansible-acme-sh?

It is an [Ansible](http://www.ansible.com/home) role to:

- Install acme.sh to issue, renew or remove Let's Encrypt based SSL certificates
- Issue certificates for single, multiple or wildcard domains
- Configure multiple domains through 1 certificate or separate certificates
- Issue DNS based challenges using acme.sh's automated DNS API feature
- Run custom acme.sh commands if the presets are not enough for you

## Why would you want to use this role?

This role is a fork of [nickjj/ansible-acme-sh](https://github.com/nickjj/ansible-acme-sh) with pull requests [#16](https://github.com/nickjj/ansible-acme-sh/pull/16) and [#25](https://github.com/nickjj/ansible-acme-sh/pull/25) merged.

Ansible doesn't complain about broken conditionals and your certificates are ordered from letsencrypt rather than zerossl.

snip snip ---%<--- snip snip

For more details check upstream.
