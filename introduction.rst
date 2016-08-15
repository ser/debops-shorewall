Introduction
============

The ``debops.shorewall`` role is used to install, configure and manage
`Shorewall <http://shorewall.org>`_, a gateway/firewall configuration tool for
GNU/Linux. 

The Shoreline Firewall, more commonly known as “Shorewall”, is high-level tool
for configuring Netfilter. You describe your firewall/gateway requirements using
entries in a set of configuration files. Shorewall reads those configuration
files and with the help of the iptables, iptables-restore, ip and tc utilities,
Shorewall configures Netfilter and the Linux networking subsystem to match your
requirements. Shorewall can be used on a dedicated firewall system, a
multi-function gateway/router/server or on a standalone GNU/Linux system.

Shorewall is not a daemon. Once Shorewall has configured the Linux networking
subsystem, its job is complete and there is no “Shorewall process” left running
in your system. 

Installation
~~~~~~~~~~~~

This role requires at least Ansible ``v2.0.0``. To install it, run::

    ansible-galaxy install debops.shorewall


..
 Local Variables:
 mode: rst
 ispell-local-dictionary: "british"
 End:
