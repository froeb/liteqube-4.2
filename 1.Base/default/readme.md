This is where all our changes to the Debian-12-minimal templates are applied.

debian-core contain all the changes to the debian-12-minimal template, I assume.
So that after installing the Qubes minimal template, 
these files here are copied into the newly created qube/vm,
effectively overwriting the original content.

I read at one point that the core qube/vm should be much smaller than the qubes minimal templates
as these are not so minimal after all. I wonder where/how the deleting part is implemented.

Form the files in this directory, we need to imolement the necessary changes for updating to denian 12.
One minimal change we can do right now is to update the sources file inthe  debian-core/apt directory.

dom0/etc/qubes-rpc contains changes/adaptions how qubes should handle the created lite Qube/vm
