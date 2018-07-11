# ho-ansible/ssh
Ansible role to configure ssh client/server

# Dependencies

# Role variables
+ `ssh_port` (default: 22): TCP port server listens on
+ `ssh_whitelist` (default: all): allow (via firewall) only these
  hosts to connect to server.  Either IPv4 or IPv6 are ok.
+ `ssh_extra_cfg`: any extra lines to put in client config
