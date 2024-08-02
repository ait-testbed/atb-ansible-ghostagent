AECID-WIN-Testbed: atb-ansible-ghostsagent
=========

This roles installs and sets up the GHOSTS-NPC agent for user simulation on the clients

Requirements
------------

.NET 4.8 or higher on the Windows host

Role Variables
--------------

```yaml
apps:
  - dotnet
  - firefox
  - 7zip
  - filezilla

GhostsServerIP: {{ ghostserverip }}
```

Dependencies
------------

pywinrm

Example Playbook
----------------
```yaml
- hosts: clients
  roles:
      - role: atb-ansible-ghostagent
```
License
-------

MIT

Author Information
------------------

Sebahattin Sahin
