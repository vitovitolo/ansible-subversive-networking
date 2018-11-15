# ansible-subversive-networking

Ansible repo to install tools for subversive networking project

# How to use it?

Tested on debian 9

1 - Install git and ansible
```
$ apt-get install git python-pip
$ pip install ansible==2.6.3
```

3 - Clone repo
```
$ git clone https://github.com/vitovitolo/ansible-subversive-networking.git
```

4 - Apply Playbook
```
$ cd ansible-subversive-networking
$ ansible-playbook -i inventory playbooks/all.yml -D
```
