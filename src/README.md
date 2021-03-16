# Overview

This subordinate charm provides the Manila Dashboard plugin for use with the OpenStack Dashboard.

# Usage

Example minimal deploy:

    juju deploy cs:openstack-dashboard --config openstack-origin=cloud:bionic-train
    juju deploy cs:manila-dashboard
    juju add-relation openstack-dashboard:dashboard-plugin manila-dashboard:dashboard

# Bugs

Please report bugs on [Launchpad](https://bugs.launchpad.net/charm-manila-dashboard/+filebug).

For general questions please refer to the OpenStack [Charm Guide](https://docs.openstack.org/charm-guide/latest/).
