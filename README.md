# Ansible ldap client role
This role aims to setup ldap authentication on a server using libnss-ldapd.

## Dependencies
None.

## Role variables (see defaults/main.yml for default values)
* `ldap_client_packages_state`: State of the packages to install.
* `ldap_client_ldap_uri`: URI of the LDAP server.
* `ldap_client_ldap_base_dn`: Base DN of the LDAP server.
* `ldap_client_services`: List of services to enable LDAP for.

## License
MIT
