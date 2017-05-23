# ansible

Collection of roles and playbooks I use.

Dependencies:

* ansible
* passlib

tl;dr

    ansible-playbook -i hosts --ask-vault-pass webserver.yml

## Documentation

### Registering a domain with SSL

Note that the assumption is that you want to handle both your domain and the `www` prefix/subdomain - be sure that the CNAME is set properly for both to forward to the desired box's IP.
