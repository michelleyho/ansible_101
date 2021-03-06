# ansible_101
Basic Tutorial on how to run ansible scripts

## What is it?
* Open source automation framework - configuration management tool
* Enables large scale and ease of deployment of software
* Works on push model
  * Doens't need additional software to be installed on server
  * Manages remote connection through SSH (underneat the hood)
     
## Inventory Host files
* File that details set of host machines to play ansible playbooks on.

## CLI commands

## Playbooks
#### To run:
```bash
>> ansible-playbook -vvv <playbook_name.yml> -e "key1=value1 key2=value2 key3=value3"
>> ansible-playbook -vvv system_query.yml -e "host=machine1.inside-network.com"
>> ansible-playbook -vvv -i host_machines.ini system_query.yml -e "host=machine1.inside-network.com file_source=/home/michelleho/Documents/test_file.log"
```

## Option Flags


## Basic machine ping
```bash
>> ansible -v <host_name> -m ping
>> 
```


### Reference Material
* https://docs.ansible.com/ansible/2.3/intro.html
* https://www.educba.com/software-development/software-development-tutorials/ansible-tutorial/
