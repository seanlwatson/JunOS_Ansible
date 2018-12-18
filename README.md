# JunOS_Ansible

Example:
Create two eBGP sessions with multipath enabled and ECMP. Perform testing and verify BGP states are 'Established', 
that BGP routes exist for peer loopbacks, and that all loopbacks are reachable (via ICMP ping). This was tested in
Ansible version 2.2.3.0 and Juniper.junos Ansible Galaxy modules version 1.4.2.
Usage: ansible-playbook pb2.bgp.yml
