Overview
========

pyopenvswitch is a library for use to control and interact with [Open vSwitch](http://openvswitch.org) installations.

This library implements the following components of the Open vSwitch software package:

- vsctl
- ofctl
- dpctl

Requirements
------------

- Open vSwitch 1.10 +


Examples
--------

```sh
>>> from pyopenvswitch import vsctl
>>> vsctl.list_bridges()
>>> from pyopenvswitch import ofctl
>>> ofctl.show('br1')
>>> from pyopenvswitch import dpctl
>>> dpctl.dump_flows()
```
