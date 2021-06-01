# otus-nfs

В Vagrantfile создается две VM, provision step запускает на виртуальных машинах Ansible playbook, который настраивает nfs на сервере и клиенте. Nfs share монтируется на клиенте с помощью fstab.