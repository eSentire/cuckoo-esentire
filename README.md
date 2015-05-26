This is a vSphere/ESX machinery module for the Cuckoo sandbox and
is intended to replace Cuckoo's ESX machinery module.

It adds full memory dump functionality during analysis, which is
currently not supported by Cuckoo's LibVirt-based ESX module.

The module depends on the vSphere API Python Bindings provided by
VMware (https://github.com/vmware/pyvmomi) which can be installed
via pip:

sudo pip install --upgrade pyvmomi

