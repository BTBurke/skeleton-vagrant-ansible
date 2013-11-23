Skeleton - Vagrant + Ansible
===

This is another installment in my multi-part series of project skeletons.  This one sets you up for a generic Vagrant + Ansible development environment.  It includes:

* An amazing Vagrantfile that will cue up Anisble for devops goodness
* An Ansible inventory file that works with a stock Vagrant set up
* A vagrant.yaml file that contains the tasks you want to execute on vagrant up
* An Ansible playbook that will update your Virtualbox Guest Additions if it's not the same version as your Virtualbox on the host
