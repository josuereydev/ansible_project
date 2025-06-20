# ansible_project

/// MOSTRAR VARIABLES DE UN HOST
ansible all -i inventory.ini -m  setup | grep ansible_distribution

////LANZAR EL PLAYBOOK
ansible-playbook -i inventory.ini main.yml
