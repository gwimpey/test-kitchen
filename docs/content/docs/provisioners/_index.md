---
title: Provisioners
menu:
  docs:
    parent: provisioners
    weight: 1
---

A Test-Kitchen *provisioner* is a what takes care of configuring the compute instance provided by the *driver*. This is most commonly a configuration management framework like Chef or the Shell provisioner, both of which are included in test-kitchen by default.

Other provisioners:

 - kitchen-ansible
 - kitchen-puppet
 - kitchen-dsc