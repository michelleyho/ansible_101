# ansible_101
Basic Tutorial on how to run ansible scripts

## Inventory Host files

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
