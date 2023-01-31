Used to manage **Configuration of servers**. Configuration management tools like Ansible, Puppet, Chef, etc are used.

## Ansible

### Push Mechanism

Script can be written in 1 place and pushed whenever needed.

### Agentless

(You don't need ansible installed on the servers you are configuring with ansible - means ansible can be on any 1 machine & using it you can configure multiple machines)

(No master - slave architecture)

### Its Simple - since it uses YAML.

We can write our **own modules** & share it with others using ansible galaxy.

### Disadvantage of Ansible

1. **Windows modules** aren't that good.

2. **Debugging** is not that good.

3. Performance isn't good when you do parallel execution.

(All these are areas to improve)

## Does Ansible support AWS?

-> Yes, it supports almost all cloud providers. Only thing needed is Public IP address, ssh enabled to the machine, ssh allowed to access from ansible host.

## Puppet

1. **Pull mechanism**

2. Master-slave architecture

3. Puppet language (Used for Script)
