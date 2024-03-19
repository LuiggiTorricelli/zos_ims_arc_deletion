zos_ims_arc_deletion
=================

The Ansible role `zos_ims_arc_deletion` will perform a sequence of steps to connect to the z/OS system, check and delete specified objects related to restart control records of IMS, using the AR/CTL BCS REGISET Delete Restart Environment Utility (AESURDRE).

Requirements
============

1. ***BMC AMI Application Restart Control for Db2, IMS and VSAM*** must be installed on the remote systems to enable the usage of AR/CTL BCS REGISET Delete Restart Environment Utility (AESURDRE).

Role Variables
==============

Check the role argument specifications file [meta/argument_specs.yml](meta/argument_specs.yml).

Dependencies
============

None.

Example Playbook
=============================================

Check the example playbook file [example.yml](example.yml).

Sample Output
=============

When this role is successfully executed, the informed records were successfully deleted from the list of restart control records.

License
=======

This role is licensed under licensed under [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

Author Information
==================

This role was created in 2024 by Luiggi Torricelli, a Db2 for z/OS system programmer.
